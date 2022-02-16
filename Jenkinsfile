pipeline {
   //agent { docker {image 'python:latest' } }
   agent any
   environment {
      //dockerhome = tool 'MyDocker'
      mavenhome = tool 'MyMaven'
      PATH = "$mavenhome/bin:$PATH"
                          }
   stages {
     stage ("Build Image") {
        steps {
               //echo "$BUILD_NUMBER"
               //sh 'python --version'
                 echo "$BUILD_NUMBER"
                 echo "$PATH"
                 sh 'docker version'
                 sh 'mvn --version'
                }
       }
}
   
}
