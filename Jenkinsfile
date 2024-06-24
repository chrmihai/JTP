pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo "The value of the Environment parameter is: ${params.Environment}"
                sh 'mvn clean install'
            }
        }
        stage('Running') {
            steps {
//                 sh 'java TestClass'
            }
        }
    }
}