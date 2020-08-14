pipeline{
  agent any
   stages{
    stage('build'){
            steps{
              step /usr/bin/curl google.com
              
                }
     }
     }
  post { 
        success { 
            echo 'code is working'
        }
    }
     }
     
