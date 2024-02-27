pipeline {
    agent { node 'srvr88' }
    stages {
        stage('download the 19c software') {
            steps {
                sh 'mkdir -p /tmp/19c'
		cd '/tmp/19c'
		git clone 'https://github.com/awsgith/awsgith.git'
		cd '/tmp/19c/awsgith'
		sh 'wget.sh'
            }
        }
        stage('create file') {
            steps {
                sh 'touch /tmp/agent_test/test.sh'
            }
        }
    }
}
