pipeline{
    agent any
    stages{
        stage('Checkout Code'){
            steps{
                git 'https://github.com/SoonMingQian/test-django'
            }
        }
        stage('Build'){
            steps{
                sh 'echo "building the app"'
            }
        }
        stage('Test'){
            steps{
                sh 'echo "Running tests"'
            }
        }
        stage('Deploy'){
            steps{
                sh 'echo "Deploying"'
            }
        }
    }
}
    
