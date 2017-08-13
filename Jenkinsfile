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
          def ub = docker.image('dockerforjenkins.azurecr.io/ubuntu:shumpei')
          ub.pull()
          ub.inside{
          sh 'pwd'
          }
        }
      }
    }
  }
}
