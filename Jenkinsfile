pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh 'npm install'
      }
    }

    stage('prod') {
      steps {
        sh 'npm start'
      }
    }

  }
}