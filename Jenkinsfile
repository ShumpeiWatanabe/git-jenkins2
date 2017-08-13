pipeline {
  agent {
    node {
      label 'slavejenkins'
    }
  }
  stages {
    stage('build') {
      steps {
        def ub = docker.image('ubuntu:shumpei')
        ub.pull()
        ub.inside{
          sh 'pwd'
        }
      }
    }
  }
}
