pipeline {
  
  agent any
  
  stages {
  
    stage("build") {
    
      steps {
        echo "building the application"
        sh "sudo docker-compose build"
        sh "sudo docker-compose up"

       }
    }


    
  }
  
}