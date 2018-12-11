pipeline {
    agent any
    environment {
        CI = 'true'
    }
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
}
