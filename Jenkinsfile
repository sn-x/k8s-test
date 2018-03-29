pipeline {
  agent any
  stages {
    stage('test1') {
      parallel {
        stage('test1') {
          steps {
            sh '''#!/bin/bash

uptime'''
          }
        }
        stage('dfdff') {
          steps {
            sleep 5
          }
        }
      }
    }
    stage('') {
      steps {
        echo 'weak'
      }
    }
  }
}