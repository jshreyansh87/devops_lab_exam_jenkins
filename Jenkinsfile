pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                python -m labs.py
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