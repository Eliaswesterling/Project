pipeline {
    agent {
        docker {
            image 'node:20.9.0-alpine3.18' 
            args '-p 3000:3000' 
        }
    }
    stages {
        stage('Build') { 
            steps {
                dir('C:\application security\Docker\Project\my-app\package.json')
                sh 'npm install' 
            }
        }
    }
}