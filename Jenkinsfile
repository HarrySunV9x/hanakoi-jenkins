pipeline {
    agent any
environment {
        HTTP_PROXY = 'http://localhost:8080'
        HTTPS_PROXY = 'http://localhost:8080'
        NO_PROXY = 'localhost,127.0.0.1'
    }
    stages {
        stage('Build') {
            steps {
                bat '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}