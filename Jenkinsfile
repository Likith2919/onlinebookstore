pipeline {
    agent any
    stages {
        stage ('build') {
            steps {
                cleanWs()
                sh 'mvn clean package'
            }
        }
    }
}