pipeline{
  agent any
  stages{
    stage('Build'){
      steps{
          echo "Hey this is from master branch"
      }
    }
    stage('Pull to Main repository'){
      when{
        branch 'masterr'
      }
      steps{
          echo "Pushing master branch code to main branch"
      }
    }
  }
}
