pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        sh '''echo "Esse � meu script"
echo "N�mero: $BUILD_NUMBER"
echo "Demo: $DEMO"'''
      }
    }

  }
  environment {
    DEMO = '1'
  }
}