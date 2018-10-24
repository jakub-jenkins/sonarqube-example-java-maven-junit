pipeline {
  agent any
  stages {
    stage('compile') {
      steps {
        sh 'mvn install'
        echo 'jhgfd'
      }
    }
    stage('teztgitweb') {
      steps {
        sh 'mvn test'
      }
    }
  }
}
