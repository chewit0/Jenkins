pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Changing test text: Hello World"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}
