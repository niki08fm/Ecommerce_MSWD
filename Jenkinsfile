pipeline {
    agent any

    stages {
        stage('Checkout Code') {
            steps {
                git 'https://github.com/niki08fm/Ecommerce_MSWD.git'
                echo 'Code checked out successfully!'
            }
        }
        stage('Build') {
            steps {
                echo 'This is where the build steps will go...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'This is where the deployment steps will go...'
            }
        }
    }
}
