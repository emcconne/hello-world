pipeline {
	agent any
	stages {
		stage('Build') {
			sh 'mvn install'
		}
		post {
			always {
				echo 'stage scope'
			}
		}
	}
	post {
		always {
			echo 'pipeline scope'
		}
	}
}
