pipeline {
  agent {
    label 'docker-slave, slave12'
  }
  stages {
    stage('dev') {
      steps {
        sh 'mkdir -p /home/ubuntu/krish1'
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
