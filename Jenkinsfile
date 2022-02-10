pipeline {
   agent { docker image {python:latest}}
      stages {
        stage ('pull image' ) {
          steps {
                  sh 'python --version'
                 }
       stage ('check linux') {
           steps {
                docker images 
          }
        }         
      }
   }

}
