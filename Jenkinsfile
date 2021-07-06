pipeline {
  agent any
  stages {
    stage('run helloworld') {
      steps {
        sh 'helloworld.sh'
      }
    }

  }
  environment {
    local = 'true'
  }
}
