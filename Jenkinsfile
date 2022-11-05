pipeline {
	agent any
	stages {
		stage('build') {
			steps {
				echo 'npm install'
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