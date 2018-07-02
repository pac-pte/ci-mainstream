pipeline {
  agent any
  stages {
    stage('TE1') {
      parallel {
        stage('TE1') {
          steps {
            echo 'TE1'
          }
        }
        stage('TE2') {
          steps {
            echo 'TE2'
          }
        }
      }
    }
    stage('CrossChecking') {
      steps {
        echo 'cross checking'
      }
    }
  }
}