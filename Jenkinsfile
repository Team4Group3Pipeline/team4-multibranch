pipeline {
   agent any
   stages {
       stage('Build Code') {
           steps {
               sh 'echo "Building Artifact"'
           }
       }
      stage('Deploy Code') {
          steps {
               sh 'echo "Deploying Code"'
          }
      }
      stage('Send code to production'){
        steps {
            sh 'bash -x sudo systemctl status jenkins'
        }
      }
      stage('Pull code from Production'){
        steps {
            sh 'echo "Corrections"'
        }
      }
      stage('Push back to deployment'){
        steps {
            sh 'echo "pwd"'
        }
      }
   }
}
