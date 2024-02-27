pipeline {
    agent { node 'srvr88' }
    stages {
        stage('download the 19c software') {
            steps {
                sh 'mkdir -p /tmp/19c'
		git(
                    url: "https://github.com/awsgith/awsgith.git'",
                    branch: "main",
                    changelog: true,
                    poll: true
		    )
		    cd '/tmp/19c'
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

