pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'javac BubbleSort.java'
            }
        }
        stage('Running') {
            steps {
                sh 'java TestClass'
            }
        }
    }
}