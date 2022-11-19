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
export MAVEN_HOME=/opt/maven/apache-maven &&
export PATH=$PATH:$MAVEN_HOME/bin &&
mvn --version'''
      }
    }

  }
}