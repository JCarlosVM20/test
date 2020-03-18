pipeline {
  agent any
  stages {
    stage('QE') timeout(1){
      steps {
        sh label:'', script: '''cd ruby
rubocop'''
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
