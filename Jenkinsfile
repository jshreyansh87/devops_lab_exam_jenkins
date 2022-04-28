pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'py labs.py'
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