pipeline {
  agent {
    node {
      label 'slavejenkins'
      customWorkspace ‘/home/shumpei/’
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