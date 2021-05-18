pipeline {
  agent any

 environment {
  NOMBRE = "tere"
   
}

  stages {
    stage('compilar') {
      steps {
        sh 'javac Simple.java'
      }
     }
    stage('ejecutar'){
      steps{
        sh 'java Simple'
      }
    }
    stage('compilar param') {
      steps {
        sh 'javac Param.java'
      }
     }
    stage('ejecutar param'){
      steps{
        sh 'java Param {$NOMBRE}'
      }
    }
  }
}
