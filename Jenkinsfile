pipeline {
    agent { docker { image 'node:19.1-alpine3.16' } }
    stages {
        stage('build') {
            steps {
                sh 'node --version'
            }
        }
    }
}
