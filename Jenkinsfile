pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh 'npm install'
      }
    }

    stage('build docker') {
      steps {
        sh '          docker.build registry + ":$BUILD_NUMBER"'
      }
    }

  }
}