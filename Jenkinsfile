pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        bat '"This is new build ${BUILD_NUMBER} and {DEMO}"'
      }
    }

  }
  environment {
    DEMO = '1'
  }
}