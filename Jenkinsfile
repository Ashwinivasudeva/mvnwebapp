pipeline {
  agent any
  stages {
    stage('execute shell') {
      parallel {
        stage('execute shell') {
          steps {
            echo 'Hello'
          }
        }

        stage('Shell') {
          steps {
            sh 'echo \'Hello World\''
          }
        }

      }
    }

  }
}