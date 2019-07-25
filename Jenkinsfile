pipeline {
  agent any
  stages {
    stage('Build & Test') {
      steps {
        sh 'mvn clean install'
        tool(name: 'Maven', type: 'maven-3.6.1')
      }
    }
  }
  tools {
    maven 'maven-3.6.1'
  }
}