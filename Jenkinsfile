@Library ('lib-0@1.1')_
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
