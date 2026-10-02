pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo 'Building the application...'
                sh 'cat app.txt'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing the application...'
                sh 'test -f app.txt'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying the application...'
                sh 'echo "Application deployed successfully!"'
            }
        }
    }
}