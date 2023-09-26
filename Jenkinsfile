@Library('lib-0')
pipeline {
agent any

  stages{
    stage('Build'){
      steps{
        script{
          build()
        }
      }
    }
    stage('Deploy'){
       steps{
        script{
          deployDemo()
        }
      }
    }
  }
}
