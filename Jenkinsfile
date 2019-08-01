pipeline {
  agent none
  stages { 
    stage ('Test') {
      agent { label 'nodejs-app' }
      steps {
        container ('nodejs') {
          echo 'Hello world!'
          sh 'java -version'
        }
      }
    }
  }
}
