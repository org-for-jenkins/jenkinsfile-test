pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building.. from Build stage for GitHub hook'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing.. from Test stage for github hook'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying.... from Deploy stage for github hook'
            }
        }
    }
}
