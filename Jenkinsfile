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
        stable { 
            echo 'code is working'
        }
    }
     }
     
