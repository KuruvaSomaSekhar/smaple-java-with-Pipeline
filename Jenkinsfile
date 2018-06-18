pipeline {
  agent any
  stages {
    stage('Compile Stage') {
      steps {
        sh 'mvn clean  install compile'
      }
    }
    stage('Testing Stage') {
      steps {
        sh 'mvn test'
      }
    }
  }
}