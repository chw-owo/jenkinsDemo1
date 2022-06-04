pipeline {
  agent {
    label 'demoAgent'
  }
  stages{
    stage('test'){
      steps{
        echo '$(date +%Y)-$(date +%m)-$(date +%d) $(date +%H):$(date +%M):$(date +%S)'
      }
    }
    stage('test2'){
      steps{
        echo 'hi'
      }
    }
  }
  post{
      always{
        echo 'pipeline done'
      }
    }
}
