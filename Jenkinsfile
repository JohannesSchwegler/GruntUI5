  
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
       stage('Install SAP') {
      steps {
        bat 'npm config set @sap:registry https://npm.sap.com'
      }
    }   
    
 
     stage('Install dependencies') {
      steps {
        bat 'npm install'
      
      
      }
    }     
       stage('Run grunt') {
      steps {
        bat 'grunt'
      }
    }     
    
  }
}
