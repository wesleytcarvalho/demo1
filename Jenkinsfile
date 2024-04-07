pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        sh '''echo "Esse é meu script"
echo "Número: $BUILD_NUMBER"
echo "Demo: $DEMO"'''
      }
    }

  }
  environment {
    DEMO = '1'
  }
}