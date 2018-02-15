pipeline {
  agent any
  stages {
    stage('Stage 1') {
      parallel {
        stage('Stage 1') {
          steps {
            build 'PowershellzCopy'
          }
        }
        stage('Stage 1.5') {
          steps {
            echo 'DO IT!'
          }
        }
      }
    }
    stage('Stage 2') {
      steps {
        echo 'This is the END!'
      }
    }
  }
}