pipeline {
    agent any
     tools {nodejs "node"}
    stages {
        stage('Install Dependencies') {
          steps {
             bat 'yarn cache clean'
             bat 'yarn install --network-timeout 1000000'
             bat 'npm install --global yarn'
             bat 'npm install -g firebase-tools'
          }    
    }
}
