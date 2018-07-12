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
  stage('copy war') {
      steps {
        bat 'copy C:\Users\rathinakumar.ganesh\.jenkins\workspace\pipetest\calendar.war D:\Test\apache-tomcat-7.0.90\webapps\'
      }
    }      
  }
}
