pipeline {
  agent any
  stages {
    stage('Test') {
      steps {
        sh '''docker --version
docker-compose --version
docker run -d -p 80:80 --name webserver nginx'''
      }
    }

  }
}