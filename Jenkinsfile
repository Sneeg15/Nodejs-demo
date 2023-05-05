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
            steps {
                sh 'echo "Hi"'
            }
        }
        stage('Build') {
            steps {
                sh 'echo "Hi"'
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo "Hi"'
            }
        }
    }
}
