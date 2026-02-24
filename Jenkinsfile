pipeline {
    agent any

    stages {

        stage('Checkout') {
    steps {
        git branch: 'main',
            url: 'https://github.com/Renganayaki-tech/js-demo.git',
            credentialsId: 'github-ssh'
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

