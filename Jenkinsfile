pipeline {
    agent any
    stages {
        stage('Run Tests') {
            parallel {
                stage('checkout master') {
                    steps {
                        git branch: 'main', url: 'https://github.com/mayagolan123/cicd1.git'
                        sh 'pytest -vv'
                    }
                }
                stage('checkout branch1') {
                    steps {
                        git branch: 'branch1', url: 'https://github.com/mayagolan123/cicd1.git'
                        sh 'pytest -vv'
                    }
                }
            }
        }
    }
}
