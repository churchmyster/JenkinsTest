pipeline {
    agent any 
    stages {
        stage('Checkout'){
            staps{
                checkout scm  
            }   
        }
        stage('Build') {
            steps {
                echo 'Hello world from Jenkinsfile!'
                sh "make"
                 
            }
        }
    }
}
