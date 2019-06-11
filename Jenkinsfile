pipeline {
  agent none
  stages {
    stage('Test'){
      agent { label 'nodejs-app' }
      steps {
        container('nodejs')
        echo 'Hello World!'   
        sh 'java -version'
      }
    }
    stage('Say Hello') {
      steps {
        echo 'Hello World!'   
        sh 'java -version'
      }
    }
  }
}