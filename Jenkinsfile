pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'this is ran from ${params.environment}'
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