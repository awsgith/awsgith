pipeline {
    agent any

    stages {
        stage('create directory') {
            steps {
                sh 'mkdir -p /home/oracle/test'
            }
        }
        stage('create file') {
            steps {
                sh 'touch /home/oracle/test/test.sh'
            }
        }
    }
}

