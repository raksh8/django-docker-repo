pipeline {
  
  agent any
  
  stages {
  
    stage("build") {
    
      steps {
        echo "building the application"
        sh "docker-compose build"
        sh "docker-compose up"

       }
    }


    
  }
  
}