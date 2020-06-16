pipeline {
  agent any
  stages {
    stage('Test') {
      steps {
        sh '''docker --version
docker-compose --version
docker inspect nginx'''
      }
    }

  }
}