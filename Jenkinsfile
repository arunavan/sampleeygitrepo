pipeline {
    agent any
    options {
        // Timeout counter starts AFTER agent is allocated
        timeout(time: 1, unit: 'SECONDS')
    }
    stages {
        stage('Build') {
            steps {
                echo 'Build stage'
            }
        },
        stage('Test') {
            steps {
                echo 'Test'
            }
        },
        stage('Scan') {
            steps {
                echo 'Scan'
            }
        },
        stage('Deploy') {
            steps {
                echo 'Deploy'
            }
        },
         stage('Monitor') {
            steps {
                echo 'Monitor'
            }
        }
        
    }
}
