pipeline {
    agent any	
    stages {
        stage('Check Java Version') {
            steps {
                sh label: '', script: 'java -version'
            }
        }
          stage("Quality Gate") {
            steps {			  
                sh label: '', script: 'echo "Master Branch'
            }
          }
    }
    post { 
        always { 
            cleanWs()
             }
        }
}
