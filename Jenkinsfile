pipeline {
    agent any

	options {
        disableConcurrentBuilds()
    }

    stages {
		stage('Get webhook params'){
			steps{
				echo "Hello i am here change";
				echo "${GIT_COMMIT}";
			}
		}
    }
}