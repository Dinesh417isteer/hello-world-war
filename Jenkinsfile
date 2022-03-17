pipeline {
  agent none
  stages {
    stage('Build') {
      steps {
        sh '''#!bin/bash
mvn clean package '''
      }
    }

  }
  environment {
    DEV = 'MFA'
  }
}