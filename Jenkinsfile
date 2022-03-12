pipeline{
    agent any
    stages {
        stage('build') {
	    steps {
  		sh 'cmake .'
		sh 'make'
            }
        }
	stage('test') {
	    steps {
		sh './test'
	    }
	}
    }
}
