pipeline {

    agent {
        docker {
            image 'node:lts-bullseye-slim'
            args '-p 3000:3000'
        }
    }
   
  stages {
   
    stage("build") {
    
      steps {
           echo "building the application"
           sh "npm install"
//            sh "npm run build"
      
      }
    
    }
    
       stage("test"){
    
      steps {
         echo "testing the application"
//          sh "npm run test"
      
      }
    
    }
    
       stage("deploy"){
    
      steps {
         echo "deploying the application"
      
      }
    
    }
  
  
  }

}
