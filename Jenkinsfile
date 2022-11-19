pipeline {
  agent any
  stages {
    stage('Checkout Code') {
      steps {
        git(url: 'https://github.com/sosereyboth/hello-world.git', branch: 'master')
      }
    }

    stage('Log') {
      steps {
        sh '''ls -la &&
mvn -version'''
      }
    }

  }
}