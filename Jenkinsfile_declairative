pipeline {
        agent any
        stages {
       	   stage('Dev') {
                steps {
	          echo "Dev All"
	          }
              }
           stage('TEST') {
                steps {
                  echo " Test One"
                  }
              }
           stage('Int Test') {
                steps {
                  echo " Int Test One"
                  }
              }
    } 
       post {
          always {
              echo "I run always"
             }

          success {
             echo "I run when success"
            }

          failure {
             echo "I run in failure"
            }
 
      }

}
