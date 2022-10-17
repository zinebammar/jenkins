pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'Your code is building'
          }
        }

        stage('Parallel build') {
          steps {
            echo 'Parallel build'
          }
        }

        stage('Hello') {
          steps {
            sh 'echo "hello"'
          }
        }

      }
    }

  }
}