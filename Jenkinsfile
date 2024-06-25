pipeline {
    agent any

    tools {
        maven 'Maven 3.3.9'
    }

    stages {
        stage('Build') {
            steps {
                echo "The value of the Environment parameter is: ${params.Environment}"
                sh 'mvn clean install'
            }
        }
        stage('Running') {
            steps {
                sh 'java TestClass'
            }
        }
    }
}