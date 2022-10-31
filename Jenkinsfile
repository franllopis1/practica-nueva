#!groovy
@Library('Libreria') _
pipeline {
  agent any
  stages {
    stage('practica') {
      steps {
        practicanueva(new File ("release.yaml").eachLine listarFichero)
      }
    }
  }
}