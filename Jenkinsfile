pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git '(link unavailable)'
            }
        }
        stage('Dependency Installation') {
            steps {
                sh 'npm install'
            }
        }
        stage('Build Docker Image') {
            steps {
                sh 'docker build -t myapp . &'
            }
        }
        stage('Run Docker Image') {
            steps {
                sh 'docker run -p 3000:3000 myapp &'
            }
        }
        stage('Push Docker Image') {
            steps {
                sh 'echo "Pushing Docker image... (simulated)"'
            }
        }
    }
}
