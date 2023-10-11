pipeline{
  agent any 
  stages{
     stages('Deploy'){
    steps{
      echo "test successful"
      bat "mvn compile"
    }
  }
   stages('Build'){
    steps{
      echo "build successful"
      bat "mvn clean"
    }
   }
      stages('Test'){
    steps{
      echo "test successful"
      bat "mvn test"
    }
      }
   }
}
    
  
