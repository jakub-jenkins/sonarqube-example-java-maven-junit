pipeline {
  agent any
  stages {
    stage('compile') {
      steps {
        sh 'mvn install'
        echo 'jhgfd'
      }
    }
    stage('tezt') {
      steps {
        sh 'mvn test'
      }
    }
  }
}