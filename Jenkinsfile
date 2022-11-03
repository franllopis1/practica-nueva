pipeline {
  agent any
  stages {
    stage('practica') {
      steps {
        //sh 'var = cut -d ":" -f1,2 release.yaml'
        echo $(cut -d ":" -f1,2 release.yaml)
      }
    }
  }
}