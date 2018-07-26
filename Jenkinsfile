pipeline {
    tools {
        nodejs 'api-nodejs'
    }
    agent any
    stages {
        stage('Build') { 
            steps {
                sh 'npm install'
            }
        }
    }
}