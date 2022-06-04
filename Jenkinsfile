pipeline {
  agent {
    label 'demoAgent'
  }
  stages{
    stage('test'){
      steps{
        echo '20220605'
      }
    }
  }
  post{
      always{
        echo 'pipeline done'
      }
    }
}
