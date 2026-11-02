
pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building Java application...'
                bat 'javac HelloWorld.java'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing Java application...'
                bat 'java HelloWorld'
            }
        }

        stage('Complete') {
            steps {
                echo 'CI Pipeline completed successfully!'
            }
        }
    }
}
