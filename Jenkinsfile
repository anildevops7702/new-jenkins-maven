pipeline {
    agent any
    stages {
        stage('Compile and Clean') {
            steps {
                sh "mvn clean compile"
            }
        }
        stage('Build') {
            steps {
                sh "mvn package"
            }
        }
        stage('Test') {
            steps {
                sh "mvn test"
            }
        }
        stage('Unit Test') {
            steps {
                sh "echo 'Performing unit tests'"
                sh "echo 'Unit tests complete'"
            }
        }
        stage('Verify') {
            steps {
                sh "echo 'Performing verification'"
                sh "echo 'Verification complete'"
            }
        }
        stage('Release') {
            steps {
                sh "echo 'Performing release'"
                sh "echo 'Release complete'"
            }
        }
        stage('Delivery') {
            steps {
                sh "echo 'Performing delivery'"
                sh "echo 'Delivery complete'"
            }
        }
        stage('Deploy') {
            steps {
                sh "echo 'Performing deployment'"
                sh "echo 'Deployment complete'"
            }
        }
    }
}
