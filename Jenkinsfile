pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        sh '''echo "Esse e meu script"
echo "Numero: $BUILD_NUMBER"
echo "Demo: $DEMO"'''
      }
    }

  }
  environment {
    DEMO = '1'
  }
}