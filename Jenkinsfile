pipeline {
    agent { node 'srvr88' }
    stages {
        stage('create directory') {
            steps {
                sh 'mkdir -p /tmp/agent_test'
            }
        }
        stage('create file') {
            steps {
                sh 'touch /tmp/agent_test/test.sh'
            }
        }
    }
}
