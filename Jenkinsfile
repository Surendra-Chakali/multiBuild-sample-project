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
        branch 'Development'
      }
      steps{
          echo "Pushing master branch code to dev branch"
      }
    }
  }
}
