pipeline {
  options {
        disableConcurrentBuilds()
    }
  agent {
    node {
      label 'Windows'
      customWorkspace 'EOSBridge/EOSBridge'
    }

  }
  stages {
    stage('Build') {
      steps {
        bat 'C:\\build-scripts/EOSBridge/build.bat'
      }
    }

  }
}
