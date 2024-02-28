pipeline {
  agent any
  stages {
    stage('hello') {
      parallel {
        stage('hello') {
          steps {
            sh 'echo \'hello\''
          }
        }

        stage('') {
          steps {
            sh 'echo \'h2\''
          }
        }

      }
    }

  }
}