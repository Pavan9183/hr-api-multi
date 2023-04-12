pipeline {
  agent any
  stages{
    stage('MAIN Deploy'){
      when {
        branch "main"
      }  
      steps {
         echo "develop on deploy"
      } 
    }
     stage('DEVELOP Deploy'){
       when {
        branch "develop"
      } 
      steps {
       echo "test on deploy"
      } 
    }
    stage('TEST Deploy'){
       when {
        branch "test"
      } 
      steps {
       echo "uat on deploy"
      } 
    }
    stage('UAT Deploy'){
       when {
        branch "uat"
      } 
      steps {
       echo "production"
      } 
    }
    
  }
}  
