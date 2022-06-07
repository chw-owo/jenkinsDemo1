pipeline {
  agent {
    label 'demoAgent'
  }
  stages{
    stage('test'){
      steps{
        echo '20220607-1106'
      }
    }
  }
  post{
      always{
        echo 'pipeline done'
      }
    }
}
