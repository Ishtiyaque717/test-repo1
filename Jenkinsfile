pipeline 
{
   agent any

    stages
    {
        stage('Build') 
        {
            steps
            {
                echo 'I am building now'
            }
        }
            stage('Test') 
       {
            steps
            {
                echo 'I am1 testing now'
            }
       }
            stage('Deploy') 
        {
       
            steps
            {
                echo 'I am deploy now'
            }
        }
       stage("Test mvn")
       {
            steps
          {
                // mvn test
                sh "mvn test"
          }
       }
    }
}
