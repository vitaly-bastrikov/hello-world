pipeline {
  agent any
  stages {
    stage('log tools versions') {
      steps {
        sh '''mvn --version
git --version
java -version'''
      }
    }

  }
}