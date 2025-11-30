pipeline {
    agent any
    stages {
        stage('Checkout Code') {
            steps {
                git 'https://github.com/SoonMingQian/test-django'
            }
        }
        stage('Build') {
            steps {
                bat 'echo "building the app"'
            }
        }
        stage('Test') {
            steps {
                bat 'echo "Running tests"'
            }
        }
        stage('Deploy') {
            steps {
                bat 'echo "Deploying"'
            }
        }
    }
    post {
        success {
            bat 'echo "build successful"'
        }
        failure {
            bat 'echo "build failure"'
        }
    }
}
