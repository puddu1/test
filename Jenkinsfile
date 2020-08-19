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
            emailext body: 'A Test EMail', recipientProviders: [[$class: 'DevelopersRecipientProvider'], [$class: 'RequesterRecipientProvider']], subject: 'Test'
        }
    }
}
     
