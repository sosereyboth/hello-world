pipeline {
  agent {
    node {
      label 'built-in'
    }

  }
  stages {
    stage('Checkout Code') {
      steps {
        git(url: 'https://github.com/sosereyboth/hello-world.git', branch: 'master')
      }
    }

    stage('Maven Build') {
      steps {
        sh '''java --version &&
mvn -version'''
      }
    }

  }
}