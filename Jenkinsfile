#!groovy
@Library('Libreria') _
pipeline {
  agent any
  stages {
    stage('practica') {
      steps {
        archivo = new File("release.yaml")
        archivo.eachLine( { println it })
      }
    }
  }
}