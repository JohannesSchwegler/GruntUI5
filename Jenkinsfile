  
pipeline {
  agent any
  stages {
    stage('HelloWorld') {
      steps {
        echo 'Hello World Test'
      }
    }
     stage('Install Grunt') {
      steps {
        bat 'npm install -g grunt-cli'
      }
    }     
       stage('Install dependencies') {
      steps {
        bat '@sap:registry=https://npm.sap.com/'
      }
    }   
    
 
     stage('Install dependencies') {
      steps {
        bat 'npm install'
        bat 'npm install grunt --save-dev'
      }
    }     
    
    
  }
}
