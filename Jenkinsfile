pipeline {
    agent any

    stages {

        stage('Frontend Install') {
            steps {
                bat 'cd frontend && npm install'
            }
        }

        stage('Backend Install') {
            steps {
                bat 'cd backend && npm install'
            }
        }

    }
}
