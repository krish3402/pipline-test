pipeline {
	agent {label 'docker-slave'}
	stages {
		stage('dev') {
			steps {
				sh 'mkdir /home/ubuntu/krish'
			}
		}
		
		stage('Test') {
			steps {
				echo "Test"
			}
		}
		stage('Prod') {
			steps {
			         echo "Production"
			}
		}
	}	
}
