#!groovy
@Library('Libreria') _

pipeline {
  agent any
  stages {
    stage('practica') {
      steps {
        practica-nueva(name: "APP_JAVA-INT:", version: "0.0.5") 
      }
    }
  }
}