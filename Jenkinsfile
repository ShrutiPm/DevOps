pipeline {
   agent { docker { image 'python:latest'  }}
      stages {
        stage ('pull image' ) {
          steps {
                  sh 'python --version'
                  sh 'sleep 60'
                 }
        }         
      }
}
