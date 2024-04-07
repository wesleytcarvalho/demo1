pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        sh "echo "Esse e meu script Numero $BUILD_NUMBER Demo $DEMO"
      }
    }

  }
  environment {
    DEMO = '1'
  }
}
