pipeline {
    agent any
    stages {
        stage('version') {
            steps {
                sh 'py --version'
            }
        }
        stage('tests') {
            steps {
                sh './job.sh'
            }
        }
    }
}