pipeline {
    agent any

    stages {

        stage('Clone') {
            steps {
                echo 'Repository cloned successfully'
            }
        }

        stage('Build') {
            steps {
                sh 'docker --version'
            }
        }

        stage('Success') {
            steps {
                echo 'Webhook Trigger Working'
            }
        }
    }
}
