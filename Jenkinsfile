node("sriram-master-node") {
    def app 
    stage('Clone repository') {
        checkout scm  
    }
    stage('Build docker compose up'){
        app = docker.build("sriram1999/sriram-cicd-task1")
    }
}
