pipeline {
    agent any

    tools {

    }
    environment {
      
    }

    stages {
         stage('List of file') {
            steps {
                sh "ls"
            }
        }
        stage('Build docker latest image') {
            steps {
                sh "docker-compose up -d"
            }
        }
    }
}