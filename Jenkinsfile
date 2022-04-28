pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'pyton -m labs.py'
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