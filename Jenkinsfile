pipeline {
    agent any
    
    stages {
        stage('Print Date') {
            steps {
                sh 'date'
            }
        }
    }
    
    triggers {
        pollSCM('*/5 * * * *')
    }
}

