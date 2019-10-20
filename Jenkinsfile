pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        container('nodejs') {
          sh "echo 'Hello'"
          }
        }
      }
    }
  }
}
