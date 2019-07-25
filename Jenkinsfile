pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        tool(name: 'maven-3.6.1', type: 'mvn')
        sh 'mvn clean install'
      }
    }
  }
}