pipeline {
  agent any
  stages {
    stage('QE'){
      steps {
        sh label:'', script: '''cd ruby
rubocop ruby tests.rb'''
            }
      }
      stage('Unit Test') {
        steps {
        
        sh 'echo "prueba"'
              }
        }
    }
}
