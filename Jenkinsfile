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
        stage('Deploy') {
            steps {
                bat 'deployment'
            }
        }
    }
}
