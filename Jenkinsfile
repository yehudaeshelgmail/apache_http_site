
pipeline {
    agent { docker { image 'maven:3.8.4-openjdk-11-slim' } }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
                sh 'df -k > /tmp/dg.log'
                sh 'cat /tmp/dg.log'
                sh 'sleep 2'
            }
        }
    }
}
