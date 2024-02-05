pipeline {
  agent {
    node {
      label 'UbuntuAgent'
    }

  }
  stages {
    stage('dev') {
      steps {
        sh 'go ./...'
      }
    }

  }
}