pipeline {
    agent {
     
    }
    
    environment {
        CI = 'true'
    }
    stages {
        stage('Build') {
            steps {
                sh 'npm install --global yarn'
                sh 'yarn'
            }
        }

    }
}
