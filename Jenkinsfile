pipeline {
    agent any
    stages
    {
        stage('Composing'){
            steps {
                sh 'docker -version'
                sh 'docker-compose up --build -d'
            }
        }
    }
}
