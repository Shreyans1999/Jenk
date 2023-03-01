pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Build'
            }
        }
         stage('Test') {
            steps {
                echo 'Test'
            }
        }
         stage('deploy') {
            steps {
                echo 'deploy'
            }
        }
    }
  post
 { 
always 
{ 
emailext body: 'ajaypipeline', subject: 'apnapipeline', to: 'saklechashreyans1999@gmail.com' 
} 
}
} 

