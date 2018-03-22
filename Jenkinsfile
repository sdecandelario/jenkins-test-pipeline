pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
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