pipeline{
    agent any
    stages {
        stage('build') {
	    steps {
  		sh 'mkdir build'
		sh 'cmake --build build'
            }
        }
	stage('test') {
	    steps {
		sh './build/test'
	    }
	}
    }
}
