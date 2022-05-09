pipeline {
    agent { label 'sriram-master-node' }
    stages
    {
        stage('Composing'){
            steps {
                checkout scm
                sh 'docker version'
                sh 'docker-compose up -d'
            }
        }
    }
}
