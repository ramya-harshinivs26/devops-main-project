pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/ramya-harshinivs26/devops-main-project.git'
            }
        }
        stage('Install Dependencies') {
            steps {
                bat 'npm install'
            }
        }
        stage('Run App') {
            steps {
                bat 'node index.js'
            }
        }
    }
}
