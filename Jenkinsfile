  
pipeline {
  agent any
  stages {
    stage('HelloWorld') {
      steps {
        echo 'Hello World Test'
      }
    }
    stage('NPM install'){
      steps{
      


       bat'npm install grunt'

     bat'npm install grunt --save-dev'
      }
      
    }
  
     
       stage('Run grunt') {
      steps {
        bat 'grunt'
      }
    }     
  }
}
