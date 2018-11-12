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
    stage('deployment1') {
      steps {
        sh 'echo 1'
      }
    }
    stage('deployment2') {
      steps {
        echo '111'
      }
    }
    stage('deployment3') {
      steps {
        echo '111'
      }
    }
    stage('deployment33') {
      steps {
        echo '222'
      }
    }
    stage('deployment4') {
      steps {
        echo '333'
      }
    }
    stage('deployment5') {
      steps {
        sleep 1
        echo '333'
      }
    }
  }
}