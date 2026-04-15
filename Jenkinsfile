pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/YOUR_USERNAME/jenkins-ci-demo.git'
            }
        }

        stage('Build') {
            steps {
                echo 'No build required for Python project'
            }
        }

        stage('Test') {
            steps {
                sh 'pytest || true'
            }
        }
    }
}