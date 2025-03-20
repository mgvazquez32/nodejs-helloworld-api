pipeline {
    agent any
    tools {
        nodejs 'nodejs'
    }
    stages {
        stage('Build') {
            steps {
                echo "EJECUTAR NPM INSTALL perrote00eeee99e3ee" 
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
