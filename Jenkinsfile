pipeline {
  agent {
    label 'docker-slave'
  }
  stages {
    stage('dev') {
      steps {
        sh 'mkdir -p /home/ubuntu/krish'
      }
    }

    stage('Test') {
      steps {
        sh 'sudo apt-get install nginx -y'
      }
    }

    stage('Prod') {
      steps {
        echo 'Production'
      }
    }

  }
}