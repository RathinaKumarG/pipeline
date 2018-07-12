pipeline {
  agent any
  stages {
       stage('create file') {
      steps {
        sh 'touch testfile.txt"'
      }
    }
    stage('just echo') {
      steps {
        sh 'echo "hello"'
      }
    }
  }
}
