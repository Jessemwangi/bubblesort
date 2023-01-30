pipeline {
    agent {
    node {
      label 'node env'
    }
    }
  stages {
    stage('Initialise') {
      steps {
        sh 'echo initialization started......'
      }
    }

    stage('Build') {
      steps {
        sh 'echo build stage'
      }
    }

    stage('Test') {
      steps {
        sh 'echo testing...'
      }
    }

    stage('Push') {
      steps {
        sh 'echo push stage'
      }
    }

    stage('status') {
      steps {
        sh 'Hurray !!! Nothing runnned successfully ......'
      }
    }

  }
}
