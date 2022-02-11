pipeline {
  agent any 
  stages {
    
    stage ('checkout code') {
      steps {
        checkout scm
      }
    }
    stage ('Build') {
      steps {
        node {
            echo "Hello World"
      }
     }   
    }
  }
}
    
    
