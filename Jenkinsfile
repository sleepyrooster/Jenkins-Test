pipeline {
  agent any
  stages {
    stage ('Build') {
      steps {
      sh 'echo "HELLO WALTER"'
      sh '''
        echo "Welcome to B2"
        uname -a
        '''
      }
    }
    stage ('Test') {
      steps {
      sh 'echo "HELLO TEST USER"'
      sh '''
        echo "This IS A TEST OF THE REPO"
        ps
        '''
      }
    }
  }
}
