pipeline {
    agent { node 'srvr88' }
    stages {
        stage('download the 19c software') {
            steps {
	       echo 'mkdir -p /tmp/19c'
               sh '/usr/local/jenkins-service/workspace/shell-pipeline/copyfile.sh'
	       sh '/tmp/19c/wget.sh'
            }
        }
    }
}
