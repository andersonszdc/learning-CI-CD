pipeline {
    agent any

    tools {nodejs 'node'}

    stages {
        stage('Build') {
            steps {
                sh 'npm version'
                sh 'cd web-app'
                sh 'npm install'
            }
        }
    }
}