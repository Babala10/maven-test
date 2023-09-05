pipeline {
    agent any
    stages{
    stage('hello'){
        steps { 
            echo "hello world"
        }
  }
    stage("build"){
            steps{
               sh 'mvn clean'
            }
        }
      }
  