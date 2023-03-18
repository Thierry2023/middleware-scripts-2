pipeline {
    agent any
  stages {
    stage ("create a zip file"){
        steps {
            sh 'zip middleware-scripts-$BUILD_NUMBER * --exclude Jenkinsfile README.md'
        }
        }
    }
  }