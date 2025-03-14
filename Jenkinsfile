pipeline {
    stages {
        withCredentials([string(credentialsId: 'sentry-env', variable: 'SENTRY_KEY')])
        stage('build') {
            steps {
                sh 'echo ${SENTRY_KEY}'
            }
        }
    }
}
