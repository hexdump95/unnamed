pipeline {
  agent any

  environment {
    MESSAGE = 'Env var'
  }

  stages {
    stage('stage 1') {
      steps {
        sh 'echo $MESSAGE'
      }
    }
    
  }
}
