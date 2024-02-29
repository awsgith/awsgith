pipeline {
    agent { node 'srvr88' }
    stages {
        stage('download the 19c software') {
            steps {
	       mkdir -p /tmp/19c'
               cp /usr/local/jenkins-service/workspace/shell-pipeline/wget.sh /tmp/19c/
	       cp /usr/local/jenkins-service/workspace/shell-pipeline/19c_download.sh /tmp/19c/
	       chown oracle:oinstall /tmp/19c/19c_download.sh'
	       sh /tmp/19c/19c_download.sh'
            }
        }
    }
}
