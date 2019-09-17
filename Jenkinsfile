pipeline {
    agent any	
    stages {
        stage('Check Java Version') {
            steps {
                sh label: '', script: 'java -version'
            }
        }
          stage("Branch Name") {
            steps {			  
                sh label: '', script: 'echo "QA Branch"'
            }
          }
    }
    post { 
        always { 
            cleanWs()
             }
        }
}