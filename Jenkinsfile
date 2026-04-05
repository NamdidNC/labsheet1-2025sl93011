pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Fetching code from GitHub'
            }
        }

        stage('Build') {
            steps {
                sh 'echo Build stage running'
            }
        }

        stage('Test') {
            steps {
                sh 'python3 calculator.py'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploy stage (dummy for now)'
            }
        }
    }
}
