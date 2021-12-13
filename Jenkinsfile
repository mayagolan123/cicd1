pipeline {
  agent any 
  stages {
    stage ('checkout') {
      steps {
        git branch: 'main', url: 'https://github.com/mayagolan123/cicd1.git'
      }
    }
    stage ('build') {
      steps {
        echo 'building ..'
      }
    }
  }
}
