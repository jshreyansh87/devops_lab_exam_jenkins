pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                bat 'python main.py'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
                bat 'python main.py'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}