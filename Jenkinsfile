pipeline{
  agent any
   stages{
    stage('build'){
            steps{
                curl 'google.com'
                }
     }
     }
  post { 
        success { 
            echo 'code is working'
        }
    }
     }
     
