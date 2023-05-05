pipeline {
    agent any
    tools {nodejs 'NodeJS'}
    stages {
        stage('install dependencies') {
            steps {
                sh 'npm install'
            }
        }
        stage('Verify') {
            steps {
                sh 'npm start'
            }
        }
        stage('SonarQube SAST') {
        }
        stage('Build') {
        }
        stage('Deploy') {
        }
    }
}
