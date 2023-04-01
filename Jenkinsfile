pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'echo Build'
          }
        }

        stage('Deploy') {
          steps {
            echo 'echo Deploy'
          }
        }

      }
    }

  }
}
