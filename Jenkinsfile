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
        stage('Test') {
            steps {
                sh 'mvn test'
            }
            post {
                always {
                    junit 'target/surefire-reports/*.xml'
                }
            }
        }
    }
}