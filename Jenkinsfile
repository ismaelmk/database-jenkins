pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        script {
          def changeset = input(
            message: 'What changeset do you want to apply?',
            parameters: [
              [$class: 'StringParameterDefinition',
              name: 'input',
              description: 'changeset']
            ])

            echo "The answer is: ${changeset}"
          }

        }
      }

    }
  }