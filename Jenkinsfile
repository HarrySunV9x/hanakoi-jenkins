pipeline {
    agent any
    environment {
        HTTP_PROXY = 'http://127.0.0.1:7897'
        HTTPS_PROXY = 'http://127.0.0.1:7897'
        NO_PROXY = 'localhost,127.0.0.1'
    }
    stages {
        stage('Build') {
            steps {
                bat 'curl -I http://www.google.com'
            }
        }
    }
}
