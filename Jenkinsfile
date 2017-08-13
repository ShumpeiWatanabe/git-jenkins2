pipeline {
  agent {
    node {
      label 'slavejenkins'
    }
  }
  stages {
    stage('build') {
      steps {
        script{
          docker.image('ubuntu:shumpei').inside{
            sh 'pwd'
          }
        }
      }
    }
  }
}
