pipeline {
    agent { node 'srvr88' }
    stages {
        stage('download the 19c software') {
            steps {
               sh 'copyfile.sh'
		sh '/tmp/19c/wget.sh'
            }
        }
    }
        stage('create file') {
            steps {
                sh 'touch /tmp/agent_test/test.sh'
            }
        }
    }

