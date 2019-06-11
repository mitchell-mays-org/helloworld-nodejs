pipeline {
  agent none
  stages {
    stage('Test'){
      agent { label 'nodejs-app' }
    }
    stage('Say Hello') {
      steps {
        echo 'Hello World!'   
        sh 'java -version'
      }
    }
  }
}