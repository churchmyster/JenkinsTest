pipeline {
    agent any 
    stages {
        stage("Checkout"){
            checkout scm   
        }
        stage('Build') {
            steps {
                echo 'Hello world from Jenkinsfile!'
                sh "make"
                 
            }
        }
    }
}
