pipeline {
    agent any
    stages
    {
        stage('Clone repository') {
            checkout scm  
        }
        stage('Composing'){
            steps {
                sh 'docker -version'
                sh 'docker-compose up --build -d'
            }
        }
    }
}
