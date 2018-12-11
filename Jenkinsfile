pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "def"'
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
