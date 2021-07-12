pipeline {
    agent any
    stages {
        stage('---clean---') {
            steps {
                sh "/usr/local/bin/mvn clean"
            }
        }
        stage('--test--') {
            steps {
                sh "/usr/local/bin/mvn test"
            }
        }
        stage('--package--') {
            steps {
                sh "/usr/local/bin/mvn package"
            }
        }
    }
}
