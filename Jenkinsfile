pipeline {
	agent any
	stages {
		stage('dev') {
			steps {
				git 'https://github.com/krish3402/maven-multi-modules.git'
			}
		}
		
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
