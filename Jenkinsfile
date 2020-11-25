pipeline {
  agent any
  stages {
    stage('build') {
      parallel {
        stage('build') {
          steps {
            sh 'echo "hola"'
          }
        }

        stage('build1') {
          steps {
            sh 'ls -la'
          }
        }

      }
    }

  }
}