pipeline {
  agent any
  stages {
    stage('practica') {
      steps {
        sh 'echo La version $(cut -d ":" -f1 release.yaml | grep INT) es $(cut -d ":" -f2 release.yaml | grep 5)'
        sh 'echo La version $(cut -d ":" -f1 release.yaml | grep PRE) es $(cut -d ":" -f2 release.yaml | grep 6)'
        sh 'echo La version $(cut -d ":" -f1 release.yaml | grep PRO) es $(cut -d ":" -f2 release.yaml | grep 7)'
      }
    }
  }
}