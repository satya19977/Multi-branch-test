pipeline{
  agent any
  stages{
    stage('multibranchtest'){
      steps{
        echo "This is file from ${env.BRANCH_NAME}"
      }
    }
  }
}
