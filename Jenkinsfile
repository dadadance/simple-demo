pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/dadadance/simple-demo.git'
            }
        }
        stage('Build') {
            steps {
                sh "echo Building..."
            }
        }
        stage('Test') {
            steps {
                sh "echo Running tests..."
            }
        }
        stage('Deploy') {
            steps {
                sh "echo Deploying..."
            }
        }
    }
}
