pipeline {
   //agent { docker { image 'python:latest'  }}
     agent any
      stages {
        stage ('pull image' ) {
          steps {
                  //sh 'python --version'
                  //sh 'sleep 60'
             echo ${JOB_NAME}
             echo ${BUILD_NUMBER}
             echo ${BUILD_URL}
                 }
        }         
      }
}
