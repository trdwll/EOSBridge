pipeline {
  options {
        disableConcurrentBuilds()
    }
  agent {
    node {
      label 'Windows'
    }

  }
  stages {
    stage('Build') {
      steps {
        bat 'C:\\build-scripts\\EOSBridge-build.bat'
      }
    }

  }
}
