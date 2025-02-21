pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Build') {
            steps {
                echo 'Build done'
                bat 'javac exJava.java'
            }
        }
        stage('Test') {
            steps {
                echo 'Test done'
            }
        }
        stage('Run') {
            steps {
                echo 'Running.com '
                bat 'java exJava'
            }
        }
    }
}
