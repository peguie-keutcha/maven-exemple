pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                git branch: 'main', credentialsId: 'ea7dc433-5fb5-4a1b-914d-828e1ec1101f', url: 'https://github.com/peguie-keutcha/maven-exemple.git'
            }
        }
    }
}