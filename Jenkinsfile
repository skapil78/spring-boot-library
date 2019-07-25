pipeline {
  agent any
  stages {
    stage('Build & Test') {
      steps {
        tool(name: 'Maven', type: 'Maven')
        sh 'mvn clean install'
      }
    }
  }
}