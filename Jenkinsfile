pipeline {
    agent any
    tools {NodeJS "node"}
    stages {
        stage('install dependencies') {
            steps {
                sh 'npm install'
            }
        }
    }
}
