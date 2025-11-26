pipeline {
  agent any
  stages {
    stage('buzz build') {
      steps {
        bat 'echo test1'
      }
    }

    stage('buzz test') {
      steps {
        sh 'echo test2'
      }
    }

  }
}