pipeline {
    stages {
        stage('build') {
            withCredentials([string(credentialsId: 'sentry-env', variable: 'SENTRY_KEY')])
            steps {
                sh 'echo ${SENTRY_KEY}'
            }
        }
    }
}
