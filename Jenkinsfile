#!groovy
@Library('Libreria') _
pipeline {
  agent any
  stages {
    stage('practica') {
      steps {
        sh '''cod=cut -f1 release.yaml
        echo $cod
        '''
        }
      }
    }
  }