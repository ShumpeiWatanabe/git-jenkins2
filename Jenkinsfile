node(‘slavejenkins’){
  stage('build'){
    checkout scm
    sh 'ls -lr'
    sh 'python helloworld.py'
  }
}
