@Library ("Second MultiBranch") _
pipeline{
  agent any
  stages{
    stage('Build'){
      steps{
        echo "Hey this is from master branch"
        secmultibranch()
      }
    }
  }
}
