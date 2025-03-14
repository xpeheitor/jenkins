pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                withCredentials([string(credentialsId: 'sentry-env', variable: 'SENTRY_KEY')]) {
                    sh 'echo ${SENTRY_KEY}'
                }
            }
        }
    }
}
