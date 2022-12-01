pipeline{
  agent any
  stages{
    stage('1-buid'){
      steps{
        sh 'df -h'
      }
    }
    stage('2-test'){
      steps{
        echo 'mvn test'
      }
    }
    stage('3-deploy'){
      steps{
        echo 'End of pipeline'
      }
    }
  }
}