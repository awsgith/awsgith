pipeline {
    agent { node 'srvr88' }
    stages {
        stage('download the 19c software') {
            steps {
	       sudo 'mkdir -p /tmp/19c'
               sudo 'cp /usr/local/jenkins-service/workspace/shell-pipeline/wget.sh /tmp/19c/'
	       sudo 'cp /usr/local/jenkins-service/workspace/shell-pipeline/19c_download.sh /tmp/19c/'
	       sudo 'chown oracle:oinstall /tmp/19c/19c_download.sh'
	       sudo 'sh /tmp/19c/19c_download.sh'
            }
        }
    }
}
