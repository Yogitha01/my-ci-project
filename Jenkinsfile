pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/Yogitha01/my-ci-project'
            }
        }
        stage('Build') {
            steps {
                echo 'Building the project...'
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests (simulated)...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying the web app (simulated)...'
            }
        }
    }

    post {
        success {
            echo '✅ Build completed successfully!'
        }
        failure {
            echo '❌ Build failed!'
        }
    }
}
