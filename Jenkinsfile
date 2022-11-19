pipeline {
  agent any
  stages {
    stage('copy build artifact') {
      steps {
        sshPublisher()
      }
    }

  }
}