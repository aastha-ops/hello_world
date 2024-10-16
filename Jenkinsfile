pipeline {
    agent any 

    stages {
        stage('Checkout') {
            steps {
     
                checkout scm
            }
        }
        stage('Build') {
            steps {
                echo 'Building the application...'
                
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
               
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying the application...'
               
            }
        }
    }
    post {
        success {
            echo 'Build and Deployment Successful!'
        }
        failure {
            echo 'Build or Deployment Failed.'
        }
    }
}
