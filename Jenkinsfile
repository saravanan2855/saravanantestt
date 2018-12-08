pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                sh ''' df -h ''' 
            }
        }
        stage('Test') { 
            steps {
                sh ''' free -m '''
            }
        }
        stage('Deploy') { 
            steps {
                sh ''' date '''
            }
        }
    }
}
