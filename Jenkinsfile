pipeline {
  agent any
  stages {
    stage('Initialize') {
      parallel {
        stage('Initialize') {
          steps {
            echo 'This is a test Pipeline'
          }
        }
        stage('In1') {
          steps {
            echo 'In1'
          }
        }
      }
    }
    stage('Build ') {
      steps {
        echo 'This is build step'
      }
    }
    stage('Report') {
      steps {
        echo 'Sample report'
      }
    }
  }
}