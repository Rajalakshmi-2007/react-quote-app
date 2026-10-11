pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                echo 'Checking out React project from GitHub...'
            }
        }

        stage('Compile') {
            steps {
                echo 'Compiling react source code...'
            }
        }

        stage('Test') {
            steps {
                echo 'Checking compiled react classes...'
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
            echo ' React Quote App'
            echo ' CI/CD PIPELINE SUCCESSFUL'
            echo '======================================'
        }

        failure {
            echo '======================================'
            echo ' React Quote App'
            echo ' CI/CD PIPELINE FAILED'
            echo '======================================'
        }
    }
}
