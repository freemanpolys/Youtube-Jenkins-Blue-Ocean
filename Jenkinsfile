pipeline {
  agent any
  stages {
    stage('Hello World') {
      steps {
        tool 'maven363'
        sh 'mvn --version'
      }
    }

    stage('Mvn okay') {
      steps {
        pwd(tmp: true)
      }
    }

  }
}