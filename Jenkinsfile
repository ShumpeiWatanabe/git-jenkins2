
pipeline {
    agent { label 'slavejenkins' } 
    stages {
        stage('Example Build') {
            steps {
		checkout scm
		sh ‘python helloworld.py’
            }
        }
    }
}
