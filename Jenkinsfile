pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
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