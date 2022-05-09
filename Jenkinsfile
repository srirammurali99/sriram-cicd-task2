node("sriram-master-node") {
    def app 
    stage('Clone repository') {
        checkout scm  
    }
    stage('Build docker compose up'){
        steps {
            sh 'docker -version'
            sh 'docker-compose up -d'
          }
    }
}
