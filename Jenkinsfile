  
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
        bat 'grunt'
      }
    }     
  
    
 
     stage('Install dependencies') {
      steps {
        bat 'npm install grunt --save-dev'
      
      
      }
    }     
    
    
     stage('Install NPM') {
      steps {
        bat 'npm install'
      
      
      }
    }  
       stage('Run grunt') {
      steps {
        echo 'Implementieren'
      }
    }     
    
  }
}
