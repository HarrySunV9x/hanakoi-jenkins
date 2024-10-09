pipeline {
    agent any
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