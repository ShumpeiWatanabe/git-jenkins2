pipeline {
  agent {
    node {
      label 'slavejenkins'
    }
  }
  stages {
    stage('build') {
      steps {
        sh 'pip --version'
        sh 'python --version'
      }
    }
  }
}