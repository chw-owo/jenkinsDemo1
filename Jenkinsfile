pipeline {
  agent {
    label 'demoAgent'
  }
  stages{
    stage('test'){
      steps{
        echo '20220607-11:25'
      }
    }
  }
  post{
      always{
        echo 'pipeline done'
      }
    }
}
