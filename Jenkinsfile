pipeline {
  agent any
  stages {
    stage('') {
      steps {
        tool(name: 'maven-3.6.1', type: 'maven')
        sh 'mvn clean install'
      }
    }
  }
}