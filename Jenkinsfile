pipeline {
    agent any

    stages {
        stage('create directory') {
            steps {
                sh 'mkdir -p /home/ubuntu/webhook'
            }
        }
        stage('create file') {
            steps {
                sh 'touch /home/ubuntu/webhook.sh'
            }
        }
    }
}

