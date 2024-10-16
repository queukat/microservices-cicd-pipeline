pipeline {
    agent any
    stages {
        stage('Clone...') {
            steps {
                git 'https://github.com/yourusername/automated-deployment-pipeline.git'
            }
        }
        stage('Build Docker') {
            steps {
                sh 'docker build -t myapp:latest .'
            }
        }
        stage('Run tests') {
            steps {
                sh 'docker run myapp:latest pytest tests/'
            }
        }
        stage('Deploy') {
            steps {
                sh 'docker run -d -p 5000:5000 myapp:latest'
            }
        }
    }
}