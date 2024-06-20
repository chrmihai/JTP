pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'this is ran from ${Environment}'
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