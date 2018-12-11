pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "br2"'
            }
        }
        stage('Test') {
            steps {
                sh 'echo "test"'
            }
        }
    }
    post {
    	cleanup{
        	deleteDir()
    	}
	}
}
