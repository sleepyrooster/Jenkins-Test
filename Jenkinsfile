pipeline {
  agent any
  stages {
    stage ('Build') {
      steps {
      sh 'echo "HELLO WORLD"'
      sh '''
        echo "This will list current dir content from latest"
        ls -lh
        echo $UID
        '''
      }
    }
    stage ('Test') {
      steps {
      sh 'echo "HELLO TEST"'
      sh '''
        echo "This list current dir"
        pwd
        '''
      }
    }
  }
}
