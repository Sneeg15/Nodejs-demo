pipeline {
    agent any
    tools {nodejs 'NodeJS'
           //maven 'Maven'
           //sonarqube 'SonarQube'
          }
    stages {
        stage('install dependencies') {
            steps {
                sh 'npm install'
                //sh 'maven clean install'
            }
        }
        stage('Archieve application zip') {
            steps {
                sh 'rm -rf *.tar.gz'
                sh 'tar czf demo_app_$BUILD_NUMBER.tar.gz node_modules main.js package.json LICENSE public'
            }
        }
        stage('Build') {
            steps {
                sh 'echo "Hi"'
            }
        }
        stage('Dependency tracker') {
            steps {
                sh 'echo "Hi"'
            }
        }
        stage('SonarQube SAST') {
            steps {
                sh 'echo "Hi"'
            }
        }
        stage('Artifact versioning & push') {
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
    post{
        success {
            sh 'echo success'
        }
        failure {
            sh 'echo failure'
        }
    }
}
