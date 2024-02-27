pipeline {
    agent { node 'srvr88' }
    stages {
        stage('download the 19c software') {
            steps {
	       echo 'sudo mkdir -p /tmp/19c'
               echo 'sudo cp /usr/local/jenkins-service/workspace/shell-pipeline/*.sh /tmp/19c'
	        sh '/tmp/19c/19c_download.sh'
            }
        }
    }
}
