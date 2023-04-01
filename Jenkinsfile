pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            bat '    bat "\\"${tool \'MsBuild\'}\\" "HelloJenkinsProject\\\\HelloJenkinsProject.sln" /p:Configuration=Debug /p:Platform=Platform -t:build"'
          }
        }

        stage('Deploy') {
          steps {
            echo 'Deployinggggg'
          }
        }

      }
    }

  }
}