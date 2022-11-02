#!groovy
@Library('Libreria') _
pipeline {
  agent any
  stages {
    stage('practica') {
      steps {
        sh 'var = cut -d " " -f1,2 release.yml'
        echo $var
      }
    }
  }
}