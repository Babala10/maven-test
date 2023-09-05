pipeline {
    agent any
    tools{
        maven 'M2_HOME'
    }
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
  