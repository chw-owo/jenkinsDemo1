pipeline {
  agent {
    label 'demoAgent'
  }
  stages{
    stage('test'){
      steps{
        echo '20220607-1105'
      }
    }
  }
  post{
      always{
        echo 'pipeline done'
      }
    }
}
