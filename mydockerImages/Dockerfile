pipeline {
  agent {
    docker { image 'my_first_image:latest' }
  }
  stages {
    stage('Test') {
      steps {
        sh 'node --version'
      }
    }
  }
}
