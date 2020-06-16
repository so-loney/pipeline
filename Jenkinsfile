pipeline {
  agent {
    docker {
      image 'nginx'
      args '-p 82:80'
    }

  }
  stages {
    stage('Test') {
      steps {
        echo 'hello'
        sh 'echo world'
      }
    }

  }
}