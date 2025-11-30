pipeline {
    agent any
    stages {
        stage('Checkout Code') {
            steps {
                sh 'echo "checkout code"'
            }
        }
        stage('Build') {
            steps {
                sh 'echo "building the app"'
            }
        }
        stage('Test') {
            steps {
                sh 'echo "Running tests"'
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo "Deploying"'
            }
        }
    }
    post {
        success {
            sh 'echo "build successful"'
        }
        failure {
            sh 'echo "build failure"'
        }
    }
}
