pipeline {
    agent { docker { image 'node:18.0.0-alpine' } }
    stages {
        stage('build') {
            steps {
                sh 'node --version'
            }
        }
    }
}
