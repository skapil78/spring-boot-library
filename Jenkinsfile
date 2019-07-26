pipeline {
  agent any
  tools{
    'maven-3.6.1'
  }
  stages {
    stage('Build & Test') {
      steps {
        sh 'mvn clean install'
      }
    }
  }
}
