pipeline {
  agent any
  stages {
    stage('Build & Test') {
      steps {
        sh 'mvn clean install'
        tool(name: 'Maven', type: 'Maven')
      }
    }
  }
}