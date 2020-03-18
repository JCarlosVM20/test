pipeline {
  agent any
  stages {
    stage('QE'){
      steps {
        sh 'cd ruby'
        sh 'rubocop || true'
            }
      }
      stage('Unit Test') {
        steps {
        
         sh 'ruby ruby/tests.rb || true'
              }
        }
    }
}
