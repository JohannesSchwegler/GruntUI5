  
pipeline {
  agent any
  stages {
    stage('HelloWorld') {
      steps {
        echo 'Hello World Test'
      }
    }
     stage('Install dependencies') {
      steps {
        bat 'npm i -save express'
      }
    }     
    
    
  }
}
