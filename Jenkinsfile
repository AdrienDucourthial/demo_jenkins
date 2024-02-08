pipeline{
  agent { any }
  environment {
    NAME = "Adrien"
  }
  stages{
    stage("Hello"){
      steps{
        echo "hello ${env.NAME}"
      }
    }
  }
}