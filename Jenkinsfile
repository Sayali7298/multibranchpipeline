pipeline{
      agent any
       stages{
             stage('smoke testing')
        {
            steps{
                sh 'echo "test Code"'
            }
        }
        
        stage('Integration testing'){
            steps{
               script {
                   if(params.Release)
                   {
                        echo "test code as integration"
          }
        }
    }
}
       }
}
