pipeline {
    agent any

    stages {
        stage('Git SCM') {
            steps {
                git branch: 'main', url: 'https://github.com/jmalahmad/espsjuin2023.git'
            }
        }
        stage('Run') {
            steps {
                echo 'Running'
                sh 'mvn clean install'
            }
        }
    }
}
