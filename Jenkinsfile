pipeline {
  agent any
  stages {
    stage('Build') {
      agent {
        docker {
          image 'node:6.3'
        }

      }
      steps {
        sh 'npm --version'
      }
    }
  }
}