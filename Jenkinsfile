pipeline {
  agent any
  stages {
    stage('practica') {
      steps {
        //sh 'var = cut -d ":" -f1,2 release.yaml'
        sh 'echo La version $(cut -d ":" -f1 release.yaml) es $(cut -d ":" -f2 release.yaml)'
      }
    }
  }
}