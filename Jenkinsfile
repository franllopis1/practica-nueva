#!groovy
@Library('Libreria') _
pipeline {
  agent any
  stages {
    stage('practica') {
      steps {
        script{
          sh "cut -d " " -f1,2 release.yaml | grep INT"
        }
      }
    }
  }
} 