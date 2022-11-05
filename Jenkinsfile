pipeline {
	agent any
	stages {
		
		
		stage('build') {
			steps {
				sh 'npm install'
				sh './jenkins/scripts/build.sh'
			}
		}
		

		stage('compile_stage') {
			steps {
				echo 'Hello 2'
			}
		}
		

		stage('unit_test_stage') {
			steps {
				echo 'Hello 3'
			}
		}
	


	}
}