pipeline {
  agent any
  stages {
    stage('test1') {
      parallel {
        stage('test1') {
          steps {
            sh 'hostname && uptime'
          }
        }
        stage('dfdff') {
          steps {
            sleep 5
          }
        }
      }
    }
    stage('error') {
      steps {
        echo 'weak'
      }
    }
  }
}