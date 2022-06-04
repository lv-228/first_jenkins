pipeline {
    agent { docker { image 'golang:1.18.3-alpine' } }
    stages {
        stage('build') {
            steps {
                sh 'go version'
            }
        }
    }
}