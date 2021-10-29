pipeline {
  agent any
  stages {
    stage('log tools versions') {
      parallel {
        stage('log tools versions') {
          steps {
            sh '''mvn --version
git --version
java -version'''
          }
        }

        stage('check for POM') {
          steps {
            fileExists 'pom.xml'
          }
        }

      }
    }

  }
}