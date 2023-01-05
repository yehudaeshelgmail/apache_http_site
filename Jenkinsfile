pipeline {
  agent {label "yehuda"}
    stages {
        stage('build') {
            steps {
                sh 'df -k > /tmp/dg.log'
            }
        }
    }
}
