pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/santamonika-111/Jenkins-Docker_project.git'
            }
        }

        stage('Build') {
            steps {
                echo "Building the application..."
            }
        }

        stage('Test') {
            steps {
                echo "Running tests..."
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploying the application..."
            }
        }
    }
}

