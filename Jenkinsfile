

pipeline {
  agent any
    tools {nodejs "nodejs v.13.1.0"}
  stages {
    stage('HelloWorld') {
      steps {
        echo 'Hello World Test'
      }
    }
    
    stage('Package and Install') {
      steps {
         bat 'npm install -g grunt-cli'
         bat' npm install grunt'
      }
    }
    
    stage('Build') {
      steps {
         bat'grunt'
      }
    }
    
  }
}
