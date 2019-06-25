pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Jekins Minute Pipeline'
      }
    }
    stage('Test') {
      environment {
        CI = 'true'
      }
      steps {
        sh './jenkins/scripts/test.sh'
      }
    }
  }
}