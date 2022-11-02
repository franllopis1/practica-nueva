#!groovy
@Library('Libreria') _
pipeline {
  agent any
  stages {
    stage('practica') {
      steps {
        script{
          datas = readYaml (file: "release.yaml")
        }
          echo datas.ear_file.deploy.toString()
        }
      }
    }
  }