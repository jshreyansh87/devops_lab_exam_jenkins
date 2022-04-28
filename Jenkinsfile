pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'python -m labs.py'
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