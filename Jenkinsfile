pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh 'bash mnp'
      }
    }

    stage('test') {
      steps {
        sh 'bash aws'
      }
    }

    stage('deploy') {
      steps {
        sh 'bash devops'
      }
    }

  }
}