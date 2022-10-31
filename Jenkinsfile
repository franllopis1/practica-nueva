#!groovy
@Library('Libreria') _
pipeline {
  agent any
  stages {
    stage('practica') {
      steps {
        new File ("release.yaml").eachLine listar
        def listar = { println $it}
      }
    }
  }
}