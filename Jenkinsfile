pipeline {
  agent any
    
  tools {nodejs "nodejs"}
    
  stages {
        
    stage('Git') {
      steps {
        git 'https://github.com/dhimzikri/hello-jenkins1.git'
      }
    }
     
    stage('Build') {
      steps {
         bat 'node app.js'
      }
    }  
    
    stage('Test') {
      steps {
        bat ''
      }
    }
  }
}