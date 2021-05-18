pipeline {
  agent any

 environment {
  nombre = "tere"
   
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
    stage('compilar') {
      steps {
        sh 'javac Param.java'
      }
     }
    stage('ejecutar'){
      steps{
        sh 'java Param'
      }
    }
  }
}
