pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo "The value of the Environment parameter is: ${params.Environment}"
                sh 'javac TestClass.java'
            }
        }
        stage('Running') {
            steps {
                sh 'java TestClass'
            }
        }
    }
}