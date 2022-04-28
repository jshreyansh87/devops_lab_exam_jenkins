pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                values_to_print=$(python labs.py)
                echo "$values_to_print"
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