pipeline {
  agent {
    docker {
      image 'nginx'
      args '-p 80:80'
    }

  }
  stages {
    stage('Test') {
      steps {
        sh '''docker --version
docker-compose --version'''
      }
    }

  }
}