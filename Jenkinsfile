pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          agent any
          steps {
            echo 'Hello from machin'
          }
        }

        stage('') {
          steps {
            echo 'hello'
          }
        }

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