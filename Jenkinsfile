pipeline {
    agent { any {
                image 'maven:3.1.1' }
            tools {
                    maven 'Maven 3.1.1'
                    jdk 'jdk8'
                }}
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}