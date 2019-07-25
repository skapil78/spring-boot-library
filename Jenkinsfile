pipeline {
  agent any
  tools {
    maven 'M3'
  }
  stages {
    stage('Build & Test') {
      steps {
        sh 'mvn clean install'
      }
    }
  }
}
