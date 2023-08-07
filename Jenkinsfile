pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        sh 'bat --version'
      }
    }
    stage('hello') {
      steps {
        sh 'bat hello.ps1'
      }
    }
  }
}