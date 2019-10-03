pipeline {
    agent { docker 'any' }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}
