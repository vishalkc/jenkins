pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        echo 'This is $BUILD_NUMBER of demo $DEMO'
        sh 'echo "This is build $BUILD of demo $DEMO"'
      }
    }

  }
  environment {
    DEMO = '1'
  }
}