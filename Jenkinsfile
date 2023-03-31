pipeline {
    agent any
    
    stages {
        stage('Print the Date') {
            steps {
                sh 'date'
            }
        }
    }
    
    triggers {
        pollSCM('*/5 * * * *')
    }
}

