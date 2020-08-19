pipeline {
  agent any
   stages {
    stage('build') {
            steps {
              echo 'Hello World'
                  }
                   }
          }
  post { 
        success { 
            echo 'code is working'
            build 'up1'
            mail to: 'puddu.25@gmail.com',
            subject: 'SUCCESSFUL',
            body: 'Build Successful'
        }
    }
        }
