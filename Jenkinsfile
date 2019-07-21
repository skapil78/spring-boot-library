pipeline {
  agent none
  stages {
    stage('Build & Test') {
      steps {
        sh 'mvn clean install'
      }
    }
  }
}