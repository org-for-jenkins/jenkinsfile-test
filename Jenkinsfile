pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building.. from Build stage for GitHub webhook'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing.. from Test stage for github webhook'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying.... from Deploy stage for github webhook'
            }
        }
    }
}
