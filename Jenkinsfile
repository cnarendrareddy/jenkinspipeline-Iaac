pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Iaac testing build'
      }
    }

    stage('Test') {
      parallel {
        stage('Test') {
          steps {
            echo 'testing'
          }
        }

        stage('Deploy') {
          steps {
            echo 'deploy'
          }
        }

      }
    }

  }
}