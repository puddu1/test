pipeline {
  agent any
   stages {
    stage('build') {
            steps {
              ech 'Hello World'
              
                }
     }
     }
  post { 
        success { 
            echo 'code is working'
            build 'new_branch'
        }
    }
     }
     
