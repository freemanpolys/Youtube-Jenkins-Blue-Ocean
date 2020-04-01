pipeline {
  agent any
  stages {
    stage('Hello World') {
      steps {
        tool(name: 'maven', type: 'maven363')
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