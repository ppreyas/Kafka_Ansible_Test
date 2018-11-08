pipeline {
  agent {
    node {
      label 'master'
    }

  }
  stages {
    stage('HelloW') {
      steps {
        echo 'Hello World'
      }
    }
  }
  environment {
    dev = '1'
  }
}