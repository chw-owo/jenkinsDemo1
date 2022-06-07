pipeline {
  agent {
    label 'demoAgent'
  }
  stages{
    stage('test'){
      steps{
        echo '20220607-11시 25분'
      }
    }
  }
  post{
      always{
        echo 'pipeline done'
      }
    }
}
