pipeline {
    agent any
    tools {nodejs "TestNode"}
    stages {
        stage('Build') { 
            steps {
                sh 'npm install' 
            }
        }
    }
}