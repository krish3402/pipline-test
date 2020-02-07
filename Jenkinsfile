pipeline {
  agent {label 'slave12'}
  stages {
    stage('dev') {
      steps {
        sh 'mkdir -p /home/ubuntu/krish'
      }
    }

    stage('Test') {
      steps {
        sh '''sudo apt-get install nginx -y
sudo service nginx stop'''
      }
    }

    stage('Prod') {
      steps {
        echo 'Production'
      }
    }

  }
}
