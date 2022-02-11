pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                checkout scm

                sh 'javac HelloWorld.java'
                sh 'java HelloWorld'

            }
        }
    }
}