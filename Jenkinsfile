pipeline {
    agent {
        docker {
            image 'node:latest' 
            args '-p 3000:3000' 
            args '-u 0:0'
        }
    }
    stages {
        stage('Build') { 
            steps {
                sh 'npm install' 
                sh 'npm run build' 
            }
        }
    }
}