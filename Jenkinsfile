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
  }
  post{
      always{
        echo 'pipeline done'
      }
    }
}
