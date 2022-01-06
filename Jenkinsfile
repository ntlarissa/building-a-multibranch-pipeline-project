pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'yum install npm'
            }
        }
        stage('Test') {
            steps {
                sh './jenkins/scripts/test.sh'
            }
        }
    }
}
