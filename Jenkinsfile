pipeline {
  agent any
  stages {
    stage('After build') {
      steps {
        echo 'After build'
      }
    }

  }
  post {
    always {
      echo 'I will always say Hello again!'
    }

  }
}