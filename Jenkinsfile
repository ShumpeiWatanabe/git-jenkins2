pipeline {
  agent { label ’slavejenkins’ }
  stages {
    stage('build') {
      steps {
        sh 'pip --version'
        sh 'python --version'
      }
    }
  }
}