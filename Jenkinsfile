pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "br1"'
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
