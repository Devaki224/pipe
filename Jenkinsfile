pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo "Hello"
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
