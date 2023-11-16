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
                // Change directory to the specific project within the Jenkins workspace
                dir("/var/jenkins_home/workspace/pipeline/your-project") {
                    // Run npm install or any other build steps
                    sh 'npm install'
                    // Add more build steps if needed
                }
            }
        }
    }
}
