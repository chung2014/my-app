pipeline {
    agent any 
    stages {
        stage('--- clear ---') { 
            steps {
                sh "/usr/local/bin/mvn clean"
            }
        }
        stage('--- test ---') { 
            steps {
                sh "/usr/local/bin/mvn test"
            }
        }
        stage('--- package ---') { 
            steps {
                sh "/usr/local/bin/mvn package"
            }
        }
    }
}