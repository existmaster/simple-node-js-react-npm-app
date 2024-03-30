pipeline {
    agent any
    tools {
        nodejs 'nodejs21'
    }
    stages {
        stage('Build') {
            steps {
                sh 'npm install'
            }
        }
    }
}