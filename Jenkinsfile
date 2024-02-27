pipeline {
    agent { node 'srvr88' }
    stages {
        stage('download the 19c software') {
            steps {
	       echo 'sudo mkdir -p /tmp/19c'
               echo 'sudo cp /usr/local/jenkins-service/workspace/shell-pipeline/wget.sh /tmp/19c'
	        echo 'sudo su - oracle sh /tmp/19c/wget.sh'
            }
        }
    }
}
