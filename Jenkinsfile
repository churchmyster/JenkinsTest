pipeline {
    agent any 
    stages {
        stage('Checkout'){
            steps{
                checkout scm  
            }   
        }
        stage('Build') {
            steps {
                echo 'Hello world from Jenkinsfile!'
                sh "make"
            }
        }
        stage('Run'){
            steps{
             sh './Hello'   
            }
         }
     }
}
