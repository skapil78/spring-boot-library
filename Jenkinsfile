pipeline {
  agent any
  //tools{
  //  'maven-3.6.1'
  //}
  stages {
   stage('Build & Test') {
     steps {
       withMaven(maven: 'maven-3.6.1'){
         sh 'mvn clean install'
       }
     }
   }
 }
}
