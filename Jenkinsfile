pipeline {
  agent any
  stages {
    stage('set up') {
      steps {
        pwd()
        bat(script: 'hostname', returnStatus: true, returnStdout: true)
      }
    }
    stage('wait') {
      steps {
        sleep 5
      }
    }
  }
}