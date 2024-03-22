pipeline {
  agent {
    docker { image 'node:16-alpine' }
  }
  stages {
    stage('Test-1') {
      steps {
        sh 'node --version'
      }
    }
  }
}
