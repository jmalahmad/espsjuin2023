pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                sh 'rm -R Hello'
                sh 'mkdir Hello'
            }
        }
        stage('By') {
            steps {
                echo 'By'
                sh 'mkdir By'
            }
        }
    }
}
