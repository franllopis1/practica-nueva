#!groovy
@Library('Libreria') _
pipeline {
  agent any
  stages {
    stage('practica') {
      steps {
        sh '''cut -d ' ' -f1 release.yaml'''
        }
      }
    }
  }