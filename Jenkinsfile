pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'echo "This is Build Number ${BUILD_NUMBER} and env variable ${DEMO}"'
      }
    }

  }
  environment {
    DEMO = '1'
  }
}