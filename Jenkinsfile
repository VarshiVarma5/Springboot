pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
            bat 'mvn clean install'
            }
        }
        stage('Deploy') { 
            steps {
            bat 'java -jar C:\Users\varsh\.jenkins\workspace\mavenpipelinespringboot\target\spring-boot-initial-0.0.1-SNAPSHOT.jar'
            }
        }
    }
}
