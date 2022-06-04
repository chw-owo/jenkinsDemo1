pipeline {
  agent {
    label 'demoAgent'
  }
  stages{
    stage('test'){
      steps{
        echo '20220605-0338'
      }
    }
  }
  post{
      always{
        echo 'pipeline done'
      }
    }
}
