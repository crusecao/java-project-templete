pipeline {
    agent any
    tools {
        maven 'apache-maven-3.6.3' 
    }
    stages {
        stage('Example') {
            steps {
                bat 'mvn clean package'
            }
        }
    }
}