pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                git 'git@github.com:Renganayaki-tech/js-demo.git'
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
