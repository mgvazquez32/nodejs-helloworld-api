pipeline {
    agent any
    tools {
        nodejs 'nodejs'
    }
    stages {
        stage('Build') {
            steps {
                echo "EJECUTAR NPM INSTALL perroteee" 
                sh 'npm install'
            }
        }

        stage('Test') {
            steps {
                echo "EJECUTAR NPM TEST PUSH" 
                sh 'npm test'
            }
        }
    }
}
