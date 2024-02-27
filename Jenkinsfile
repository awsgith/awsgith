pipeline {
    agent { node 'srvr88' }
    stages {
        stage('download the 19c software') {
            steps {
                sh 'mkdir -p /tmp/19c'
		cp '/usr/local/jenkins-service/workspace/shell-pipeline/wget.sh' '/tmp/19c/'
		cd '/tmp/'
    	        sudo 'chown -R oracle:oinstall 19c'
		cd 19c
		sh 'wget.sh'
            }
        }
    }
        stage('create file') {
            steps {
                sh 'touch /tmp/agent_test/test.sh'
            }
        }
    }
}
