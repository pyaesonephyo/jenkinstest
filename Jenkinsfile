pipeline {
    agent any
     tools {nodejs "node"}
    
    
    
    
    stages {
        stage('Install dependencies') {
          steps {
             bat 'npm install --global yarn'
             bat 'yarn'
             bat 'npm install -g firebase-tools'
          }
        }
  }
}
