pipeline{
      agent any
       stages{
             stage('Build Code')
        {
            steps{
                sh 'echo "Build Code"'
            }
        }
        
        stage('Release Code'){
            steps{
               script {
                   if(params.Release)
                   {
                        echo "relase the code to artifactory"
          }
        }
    }
}
       }
}
