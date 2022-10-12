pipeline {
    agent any
    stages {
        stage ('build') {
            cleanWs()
            steps {
                sh 'mvn clean package'
            }
        }
    }
}