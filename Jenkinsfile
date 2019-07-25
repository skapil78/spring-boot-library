pipeline {
  agent any
  stages {
    stage('Build & Test') {
      steps {
        tool(name: 'Maven', type: 'maven-3.6.1')
        sh 'mvn clean install'
      }
    }
  }
}
