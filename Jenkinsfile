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
                dir('path/to/your/project') {
                    sh 'npm install'
                }
            }
        }
    }
}