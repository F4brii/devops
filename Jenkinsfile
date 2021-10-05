pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                sh 'node file.js'
            }
        }
        stage('Test') { 
            steps {
                echo 'Arranca el proceso de pruebasgit  unitarias' 
            }
        }
    }
}