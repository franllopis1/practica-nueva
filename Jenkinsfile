#!groovy
@Library('Libreria') _
pipeline {
  agent any
  stages {
    stage('practica') {
      steps {
        sh 'ls /home/jenkins/agent/workspace/Formacion/Fran/pruebajenkins@tmp/durable-014ef1a0/script.sh'
        sh 'var = cut -d ":" -f1,2 release.yaml'
        echo $var
      }
    }
  }
}