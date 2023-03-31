pipeline {
    agent any
    
    stages {
        stage('PrintDate') {
            steps {
                sh 'date'
            }
        }
    }
    
    triggers {
        pollSCM('*/5 * * * *')
    }
}

