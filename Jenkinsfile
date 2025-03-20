pipeline {
    agent any
    tools {
        nodejs 'nodejs'
    }
    stages {
        stage('Build') {
            steps {
                echo "EJECUTAR NPM INSTALL PERRO" 
                sh 'npm install'
            }
        }

        stage('Test') {
            steps {
                echo "Ejecutar npm test push PERRI" 
                sh 'npm test'
            }
        }
    }
}
