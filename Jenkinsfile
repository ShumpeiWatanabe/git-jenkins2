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
          def ub = docker.image('ubuntu:shumpei')
          ub.pull()
          ub.inside{
          sh 'pwd'
          }
        }
      }
    }
  }
}
