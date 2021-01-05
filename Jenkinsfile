pipeline {
    agent { any { image 'maven:3.1.1' } }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}