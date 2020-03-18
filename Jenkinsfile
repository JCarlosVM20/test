pipeline {
  agent any
  stages {
    stage('QE') {
      steps {
        sh 'cd ruby'
        sh 'pwd'
        sh 'rubocop'
            }
      }
      stage('Unit Test') {
        steps {
        sh 'echo "In progress"'
        sh 'ruby ruby/tests.rb'
              }
        }
    }
}
