pipeline {
    agent any
    tools {nodejs 'NodeJS'}
    stages {
        stage('install dependencies') {
            steps {
                sh 'npm install'
            }
        }
        stage('Package into zip') {
            steps {
                sh 'tar czf demo_app_$BUILD_NUMBER.tar.gz node_modules main.js package.json LICENSE public'
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
