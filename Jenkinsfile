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
          sh 'ls -l /var/run/docker.sock'
          // This step should not normally be used in your script. Consult the inline help for details.
          //withDockerRegistry([credentialsId: 'aab1025f-c719-4b62-a17c-b20422031469', url: 'https://dockerforjenkins.azurecr.io']) {
          //  def ub = docker.image('ubuntu:shumpei')
          //  ub.pull
          //  ub.inside{
          //    sh 'pwd'
          //  }
          //}
        }
      }
    }
  }
}
