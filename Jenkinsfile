pipeline {
  agent {
    node {
      label 'atslxws244'
    }

  }
  stages {
    stage('error') {
      steps {
        sh 'echo "login in $HOST_NAME ..."'
      }
    }

  }
  environment {
    HOST_NAME = 'atslxws244'
  }
}