pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo '=============================='
                echo 'Building Java Application'
                echo '=============================='

                bat 'javac Demo.java'
            }
        }

        stage('Test') {
            steps {
                echo '=============================='
                echo 'Running Java Application'
                echo '=============================='

                bat 'java Demo'
            }
        }
    }
}
