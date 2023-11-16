pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // Checkout code from Git repository
                checkout scm
            }
        }

        stage('Build') {
            steps {
                // Run npm install in the correct directory
                dir('C://application security/docker/my-app') {
                    sh 'npm install'
            }
        }
    }
}