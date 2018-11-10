pipeline {
  agent any
  stages {
    stage('checkout') {
      parallel {
        stage('checkout') {
          steps {
            echo 'hello world'
            sh 'echo "step"'
          }
        }
        stage('say hello') {
          steps {
            echo 'hello'
          }
        }
      }
    }
    stage('deploy') {
      steps {
        echo 'hello'
      }
    }
  }
}