pipeline {
    agent { docker { image 'python:3.10.1-alpine' } }

    stages {
        stage('Build') {
            steps {
                sh 'pyton --version'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}