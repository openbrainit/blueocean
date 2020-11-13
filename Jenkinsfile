pipeline {
  agent any
  stages {
    stage('Build') {
      agent any
      steps {
        echo 'Hello from machin'
      }
    }

    stage('Test') {
      agent any
      steps {
        sh 'echo "hello"'
      }
    }

    stage('Deliver') {
      steps {
        echo 'yo'
      }
    }

  }
}