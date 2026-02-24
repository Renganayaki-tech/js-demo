pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                git 'https://github.com/YOUR_GITHUB_USERNAME/js-demo-project.git'
            }
        }

        stage('Install Dependencies') {
            steps {
                bat 'npm install'
            }
        }

        stage('Run Application') {
            steps {
                bat 'npm start'
            }
        }
    }
}