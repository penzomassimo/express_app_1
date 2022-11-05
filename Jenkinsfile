pipeline {
	agent {
		docker {
			image 'node:lts-bullseye-slim'
			args '-p 3000:3000'
		}
	}
	stages {
		stage('build') {
			steps {
				echo 'Hello 1'
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
		stage('code_coverage_stage') {
			steps {
				echo 'Hello 4'
			}
		}
		stage('static_code_analysis_stage') {
			steps {
				echo 'Hello 5'
			}
		}
	}
}