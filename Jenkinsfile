pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Git repository cloned successfully.'
            }
        }
        
        stage('Dependency Installation') {
            steps {
                echo 'Dependencies installed successfully.'
            }
        }
        
        stage('Build Docker Image') {
            steps {
                echo 'Docker image built successfully.'
            }
        }
        
        stage('Run Docker Image') {
            steps {
                echo 'Docker image running successfully.'
            }
        }
        
        stage('Push Docker Image') {
            steps {
                echo 'Docker image pushed successfully.'
            }
        }
    }
    
    post {
        success {
            echo 'The pipeline has been executed successfully!'
        }
    }
}
