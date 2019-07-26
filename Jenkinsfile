pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        tool 'maven-3.6.1'
        sh 'mvn clean install'
      }
    }
  }
}