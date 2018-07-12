pipeline {
  agent any
  stages {
    stage('just echo') {
      steps {
        bat 'echo helloworldtest123'
      }
    }
        stage('list files') {
      steps {
        bat 'dir /p'
      }
    }
  stage('run bat') {
      steps {
        bat 'copy.bat'
      }
    }      
  }
}
