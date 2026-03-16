pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                echo 'Checking out code'
            }
        }

        stage('Build') {
            steps {
                bat 'javac HelloWorld.java'
            }
        }

        stage('Run') {
            steps {
                bat 'java HelloWorld'
            }
        }

    }
}
