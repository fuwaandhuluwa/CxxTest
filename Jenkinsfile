pipeline {
  agent {
    node {
      label 'atslxws244'
    }

  }
  stages {
    stage('') {
      steps {
        sh 'echo "login in $HOST_NAME ..."'
        sh '''echo "wait for update code ...."
sh "sleep 5"'''
        sh '''echo "code building "
sh "sleep 10"'''
        sh '''echo "Testing ..."
sh "sleep 10"'''
      }
    }

  }
  environment {
    HOST_NAME = 'atslxws244'
  }
}