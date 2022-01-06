pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo Hello World!!!'
            }
        }
        stage('Test') {
            steps {
                sh './jenkins/scripts/test.sh'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying'
            }
        }
    }
}
