pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                //Build your Spring Boot Application
                sh 'mvn clean install'
            }
        }
        stage('Test'){
            steps {
                sh 'mvn test'
            }
        }
    }
}