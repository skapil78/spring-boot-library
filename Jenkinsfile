pipeline {
  agent any
  stages {
    stage('Build & Test') {
      steps {
        tool(name: 'maven-3.6.1', type: 'Maven')
        sh 'mvn clean install'
      }
    }
  }
}