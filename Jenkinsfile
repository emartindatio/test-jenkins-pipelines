pipeline {
    agent any
    stages {
        stage('Checkout SCM') {
            steps {
                echo 'Starting checkout scm stage...'
                checkout scm
            }
        }
        stage('Configure') {
            steps {
                echo 'Starting configure stage...'
                sleep 10
                echo 'Configure stage completed sucessfully'
            }
        }
        stage('Build') {
            steps {
                echo 'Starting build stage...'
                sleep 10
                echo 'Build stage completed sucessfully'
            }
        }
        stage('Test') {
            steps {
                echo 'Starting test stage...'
                sleep 10
                echo 'Test stage completed sucessfully'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Starting deploy stage...'
                sleep 10
                echo 'Deploy stage completed sucessfully'
            }
        }
    }
}