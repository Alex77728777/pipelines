pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        echo 'Hello from $BUILD_NUMBER and demo is $DEMO'
      }
    }

  }
  environment {
    DEMO = '1'
  }
}