pipeline {
  agent any
  stages {
    stage('dev') {
      agent any
      steps {
        sh 'go test ./...'
      }
    }

  }
}