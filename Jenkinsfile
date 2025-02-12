pipeline {
    agent any
    environment {
        PATH = "/opt/maven/bin:$PATH"
    }
    stages {
        stage('maven build') {
            steps {
                sh 'mvn clean install'
            }
        }
    }
}
