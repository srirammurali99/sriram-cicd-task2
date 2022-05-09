node("sriram-master-node") {
    def app 
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
