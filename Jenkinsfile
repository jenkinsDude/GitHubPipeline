pipeline {
  agent any
  stages {
    stage('Stage 1') {
      parallel {
        stage('Stage 1') {
          steps {
            echo 'start stage 1'
          }
        }
        stage('Stage 1.5') {
          steps {
            build 'PowershellzCopy'
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