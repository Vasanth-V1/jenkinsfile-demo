pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Code checked out from Git'
            }
        }

        stage('Build') {
            steps {
                echo 'Build stage'
            }
        }

        stage('Test') {
            steps {
                echo 'Test stage'
            }
        }
    }

    post {
        success {
            echo 'BUILD SUCCESSFUL'
        }
        failure {
            echo 'BUILD FAILED'
        }
    }
}
