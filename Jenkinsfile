pipeline{
  agent any
  stages{
    stages('compile'){
      step{
        sh javac Helloworld.java
      }
    }
    stage('Run'){
      step{
        sh 'java Helloworld'
      }
    }
  }
}
  
