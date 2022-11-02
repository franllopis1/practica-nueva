pipeline {
  agent any
  stages {
    stage('practica') {
      steps {
        script{
          cod = cut -d { } -f1 {release.yaml}
        }
        echo cod
        }
      }
    }
  }