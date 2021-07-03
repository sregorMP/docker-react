pipeline {
  agent {
    node {
      label 'node'
    }

  }
  stages {
    stage('build') {
      steps {
        sh 'npm -v'
      }
    }

    stage('test') {
      steps {
        sh 'echo "estou testando"'
      }
    }

  }
}