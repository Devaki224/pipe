pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo "Hello"
            }
        }
        
        stage('Test') {
            steps {
                bat 'testing stage'
            }
        }
        
        stage('Staging') {
            steps {
                bat 'staging area'
            }
        }
        
        stage('Deploy') {
            steps {
                bat 'deployment'
            }
        }
    }
}
