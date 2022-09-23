pipeline {
  agent any
  stages {
    stage('stage 1') {
      steps {
        echo 'This is Build ${BUILD_NUMBER} of the jon ${DEMO} '
      }
    }

  }
  environment {
    DEMO = '1'
  }
}