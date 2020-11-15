pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World1"'
                sh 'echo "Hello World2"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}
