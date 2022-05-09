pipeline {
    agent any 
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
