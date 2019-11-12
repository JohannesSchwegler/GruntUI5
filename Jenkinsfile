  
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
        bat 'npm install grunt --save-dev'
      
      
      }
    }     
       stage('Run grunt') {
      steps {
        bash 'grunt'
      }
    }     
    
  }
}
