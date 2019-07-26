pipeline {
  agent any
  withMaven(maven: 'maven-3.6.1'){
    sh 'mvn clean install'
  }
  //agent any
  //tools{
  //  'maven-3.6.1'
  //}
  //stages {
   // stage('Build & Test') {
   //   steps {
   //     sh 'mvn clean install'
    //  }
   // }
  //}
}
