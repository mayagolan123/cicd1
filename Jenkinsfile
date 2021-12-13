pipeline {
  agent any 
  stages {
    stage ('Checkout') {
      steps {
        git branch: 'main', url: 'https://github.com/mayagolan123/cicd1'
      }
    }
    stage ('build') {
      steps {
        echo 'building ..'
      }
    }
  }
}
