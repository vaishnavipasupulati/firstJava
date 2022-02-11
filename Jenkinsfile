pipeline {
    agent any

    stages {
        stage('Hello') {
         node {
             checkout scm
             
             sh 'javac HelloWorld.java'
             sh 'java HelloWorld'
         }


            }
        }
    
