pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh 'echo test'
      }
    }

    stage('result') {
      steps {
        echo 'aaa'
      }
    }

  }
  environment {
    label = 'master'
  }
}