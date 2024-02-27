pipeline {
    agent { node 'srvr88' }
    stages {
        stage('download the 19c software') {
            steps {
               sudo sh '/usr/local/jenkins-service/workspace/shell-pipeline/copyfile.sh'
		sudo sh '/tmp/19c/wget.sh'
            }
        }
    }
}
