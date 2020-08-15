pipeline {
  agent any
   stages {
    stage('build') {
            steps {
              echo 'Hello World'
              
                }
     }
     }
  try {
        // do something that doesn't fail
        build 'up1'
        currentBuild.result = 'SUCCESS'
    } catch (Exception err) {
        currentBuild.result = 'FAILURE'
    }
    echo "RESULT: ${currentBuild.result}"
     }
     
