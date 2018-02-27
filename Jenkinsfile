pipeline {
    agent any
    stages {
        stage('Checkout') {
            checkout scm
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