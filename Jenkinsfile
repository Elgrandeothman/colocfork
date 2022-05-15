
pipeline {
    agent { docker { image 'node:16.15.0-alpine' } }
    stages {
        stage('build') {
            steps {
                sh 'node --version'
            }
        }
    }
}
