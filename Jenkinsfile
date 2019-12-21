pipeline {
	agent any
	stages {
		stage('Test') {
			steps {
				bat label: '', script: 'mvn clean deploy'
			}
		}
		stage('Prod') {
			steps {
			         echo "Production"
			}
		}
	}	
}
