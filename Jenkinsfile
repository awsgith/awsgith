pipeline {
    agent { node 'srvr88' }
    stages {
        stage('create directory') {
            steps {
                sh 'mkdir -p /tmp/test'
            }
        }
        stage('create file') {
            steps {
                sh 'touch /tmp/test/test.sh'
            }
        }
    }
}
