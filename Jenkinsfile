pipeline {
    agent any
    stages {
        stage ('build') {
            steps {
                cleanWs()
                dir('onlinebookstore') {
                    sh 'mvn clean package'
                }
            }
        }
    }
}