pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                checkout scm
                sh 'docker-compose up -d'
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}