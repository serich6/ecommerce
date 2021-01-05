pipeline {
    agent { any { image 'maven:3.1.1' } }
    tools {
        maven 'Maven311'
    }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}