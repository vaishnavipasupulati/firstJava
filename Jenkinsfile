pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                checkout scm

                sh 'javac HelloWorld.java'
                sh 'java HelloWorld'
                sh '''#!/bin/sh

echo "Hey folks"

ls -la'''
                

            }
        }
    }
}
