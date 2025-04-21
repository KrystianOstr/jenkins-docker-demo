pipeline {
    agent any

    environment {
        AUTHOR = "KRYSTIAN"
    }

    stages {
        stage('Build docker image') {
            steps {
                sh 'docker build -t nginx-test .'
                sh 'docker images | grep nginx-test'
                echo "DZIALAA!!!!!!"
            }
        }
    }
}