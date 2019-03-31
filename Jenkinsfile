pipeline {
    agent { docker { image 'docker-slave' } }
    stages {
        stage('build') {
            steps {
              sh 'ps -ef'
            }
        }
    }
}