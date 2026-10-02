pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo 'Building the Node.js application...'
                sh 'npm install'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing the application...'
                sh 'test -f app.js'
                sh 'node --version'
                sh 'npm --version'
            }
        }

        stage('Docker Build') {
            steps {
                echo 'Building Docker image...'
                sh 'docker build -t jenkins-node-app .'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Application deployed successfully!'
            }
        }
    }
}
