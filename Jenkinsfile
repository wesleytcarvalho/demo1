pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        echo 'Olá mundo, eu sou a pipeline de número: $BUILD_NUMBER'
      }
    }

  }
  environment {
    DEMO = '2'
  }
}