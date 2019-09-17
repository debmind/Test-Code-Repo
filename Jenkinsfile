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
                sh label: '', script: 'echo "Master Branch"'
            }
          }
    }
    post { 
        always { 
            cleanWs()
             }
        }
}
