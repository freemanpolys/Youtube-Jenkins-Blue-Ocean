pipeline {
  agent any
  stages {
    stage('Hello World') {
      steps {
        sh 'ls .'
      }
    }

    stage('Mvn okay') {
      steps {
        pwd(tmp: true)
      }
    }

  }
}