pipeline {
    agent any
    tools {
        maven 'M2'
    }
    stages {
        stage('Build') {
            steps {
                sh 'mvn clean package'
            }
        }
    }
}
