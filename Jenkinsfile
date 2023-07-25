pipeline {
	agent {
		docker {
			image 'python:3.10-alpine'
		}
	}
	stages {
		stage('Build') {
			steps {
				sh 'python3 ops.py'
			}
		}
	}
}
