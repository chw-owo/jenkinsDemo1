pipeline {
  agent {
    label "demoAgent"
  }
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
    stage('third'){
      steps{
        build 'demo1'
      }
    } 
  }
  post{
      always{
        echo 'pipeline done'
      }
    }
}
