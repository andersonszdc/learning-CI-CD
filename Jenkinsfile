pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'cd web-app'
                nodejs('node') {
                    sh 'npm install'
                }
            }
        }
    }
}