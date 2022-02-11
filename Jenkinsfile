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
            javac HelloWorld.java
            java HelloWorld
      }
    }
  }
}
    
    
