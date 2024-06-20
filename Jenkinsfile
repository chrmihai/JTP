pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                javac TestClass.java
            }
        }
        stage('Running') {
            steps {
                java TestClass
            }
        }
    }
}