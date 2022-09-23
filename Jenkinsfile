pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'echo "Thid is Build Number ${BUILD_NUMBER} and env variable"'
      }
    }

  }
  environment {
    DEMO = '1'
  }
}