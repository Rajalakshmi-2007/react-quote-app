pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                echo 'Checking out Java project from GitHub...'
            }
        }

        stage('Compile') {
            steps {
                echo 'Compiling Java source code...'
            }
        }

        stage('Test') {
            steps {
                echo 'Checking compiled Java classes...'
            }
        }

        stage('Package') {
            steps {
                echo 'Packaging application...'
          }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying application...'
            }
        }
    }

    post {
        success {
            echo '======================================'
            echo ' Employee Management System'
            echo ' CI/CD PIPELINE SUCCESSFUL'
            echo '======================================'
        }

        failure {
            echo '======================================'
            echo ' Employee Management System'
            echo ' CI/CD PIPELINE FAILED'
            echo '======================================'
        }
    }
}
