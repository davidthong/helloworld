pipeline {
  agent any
  stages {
    stage('validate') {
      steps {
        build 'build'
      }
    }

  }
  environment {
    local = 'true'
  }
}