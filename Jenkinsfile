pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'sudo yum install npm'
            }
        }
        stage('Test') {
            steps {
                sh './jenkins/scripts/test.sh'
            }
        }
    }
}
