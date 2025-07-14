pipeline {
  agent any
  stages {
    stage('Print message') {
      steps {
        sh '''
          echo "Pipeline has started..."
          chmod +x ./test.sh 
          ./test.sh
        '''
      }
    }

  }
}