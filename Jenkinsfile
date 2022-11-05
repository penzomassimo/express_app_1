pipeline {
	agent {
		docker { 
			image 'node:16.13.1-alpine'
			label 'my_label'
		}	
	}
	
	stages {
		
		
		stage('build') {
			steps {
				sh 'npm install'
				sh './jenkins/scripts/build.sh'
			}
		}
		

		stage('compile_stage') {
			steps {
				echo 'Hello 233e65400'
			}
		}
		

		stage('unit_test_stage') {
			steps {
				echo 'Hello 35'
				sh './jenkins/scripts/test.sh'
			}
		}
	


	}
}