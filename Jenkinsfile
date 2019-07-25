pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        tool(name: 'Maven', type: 'maven-3.6.1')
        sh 'mvn clean install'
      }
    }
  }
}