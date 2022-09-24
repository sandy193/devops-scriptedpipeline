pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'echo "This is Build Number ${BUILD_NUMBER} and env variable ${DEMO}"'
      }
    }

    stage('Test') {
      steps {
        sh 'echo "Testing phase"'
      }
    }

  }
  environment {
    DEMO = '1'
  }
}