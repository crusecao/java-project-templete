pipeline {
    agent any
    tools {
        maven 'apache-maven-3.6.3' 
    }
	    stages {
        stage('test') {
            steps {
                sh 'mvn -version'
            }
        }
    }
    stages {
        stage('Example') {
            steps {
                sh 'mvn clean package'
            }
        }
    }
}