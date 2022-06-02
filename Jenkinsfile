pipeline {
  agent any
  stages{
    stage('first'){
      steps{
        echo 'Building...'
      }
    }
    stage('second'){
      steps{
        build 'gitDemo1'
      }
    }
    post{
      always{
        echo 'pipeline done'
      }
    }
  }
