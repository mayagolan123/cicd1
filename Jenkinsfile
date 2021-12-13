pipeline {
  agent {
    docker { image 'python:3-slim' }
  }
  stages {
    stage ('Checkout') {
      steps {
        git branch: 'main', url: 'https://github.com/mayagolan123/cicd1.git'
      }
    }
    stage ('test') {
      steps {
        sh 'echo testing..'
      }
    }
  }
}
