pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        echo "This is build ${BUILD_NUMBER} and {DEMO}"
      }
    }

  }
  environment {
    DEMO = '1'
  }
}