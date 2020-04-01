pipeline {
  agent any
  stages {
    stage('Hello World') {
      steps {
        tool(name: 'maven363', type: 'maven')
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