pipeline {
	agent any
	stages {
		stage('build') {
			steps {
//				sh 'npm install'
//				sh './jenkins/scripts/build.sh'
				echo 'massimopenzo'
			}
		}
		stage('unit_test') {
			steps {
				echo 'testing the app'
				sh './jenkins/scripts/unit_testing.sh'
			}
		}
	}
}