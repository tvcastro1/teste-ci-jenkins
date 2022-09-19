pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout([$class: 'GitSCM', branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[credentialsId: 'jenkins-teste', url: 'https://github.com/tvcastro1/teste-ci-jenkins.git']]])
            }
        }
    }
}