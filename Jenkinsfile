
pipeline {
    agent { label 'slavejenkins' } 
    stages {
        stage('Example Build') {
            steps {
		checkout scm
            }
        }
        stage(‘helloworld’){
            steps{
                echo ‘helloworld’
	    }
        }
    }
}
