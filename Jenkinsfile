pipeline {
  agent any
  stages {
    stage ('Build') {
      steps {
      sh 'echo "HELLO Anj"'
      sh '''
        echo "Welcome to B2"
        uname -a
        '''
      }
    }
    stage ('Test') {
      steps {
      sh 'echo "HELLO Roxy"'
      sh '''
        echo "Wednesday is fun"
        pwd
        '''
      }
    }
  }
}
