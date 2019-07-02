pipeline {
  agent any
  stages {
    stage('Build') {
      agent {
        docker {
          args '-p 3000:3000'
          image 'node:6-alpine'
        }

      }
      steps {
        sh 'npm install'
      }
    }
  }
}