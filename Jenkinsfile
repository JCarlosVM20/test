pipeline {
  agent any
  stages {
    stage('QE') {
      steps {
        sh 'pwd'
        sh 'ruby ruby/tests.rb'
      }
    }

  }
}
