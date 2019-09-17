pipeline {
    agent any	
    stages {
        stage('Check Java Version') {
            steps {
                sh label: '', script: '''java -version && This is Master Branch'''
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
