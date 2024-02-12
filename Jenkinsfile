pipeline {
    agent any

    stages {
        stage('create Directory') {
            steps {
                sh 'mkdir -p /home/ubuntu/dirtest'
            }
        }
        stage('create file') {
            steps {
                sh 'touch /home/ubuntu/file.sh'
            }
        }
    }
}

