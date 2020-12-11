pipeline {
  agent {
    node {
      label 'atslxws244'
    }

  }
  stages {
    stage('Fist stage') {
      steps {
        echo 'This is GitHub repository'
        sh 'echo "$HOST_NAME"'
      }
    }

    stage('Second Stage') {
      parallel {
        stage('Second Stage') {
          steps {
            sleep 10
          }
        }

        stage('Another branch') {
          steps {
            build(job: 'example', wait: true)
          }
        }

      }
    }

    stage('Last stage') {
      steps {
        echo 'Demo Done'
      }
    }

  }
  environment {
    HOST_NAME = 'atslxws244'
  }
}