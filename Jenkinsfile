pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        build(job: 'Compilar', propagate: true, quietPeriod: 11, wait: true)
      }
    }

    stage('prod') {
      steps {
        sh 'npm install'
      }
    }

  }
}