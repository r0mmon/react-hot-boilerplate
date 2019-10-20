pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        container('nodejs') {
          sh "curl ipinfo.io/ip"
          }
        }
      }
    }
  }
}
