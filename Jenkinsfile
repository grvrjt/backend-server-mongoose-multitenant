pipeline {

    agent any 
   
  stages {
   
    stage("build") {
    
      steps {
           ech "building the application"
           sh "npm install"
           sh "npm run build"
      
      }
    
    }
    
       stage("test"){
    
      steps {
         ech "testing the application"
         sh "npm run test"
      
      }
    
    }
    
       stage("deploy"){
    
      steps {
         ech "deploying the application"
      
      }
    
    }
  
  
  }

}
