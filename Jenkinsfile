pipeline{
  agent { any }
  environment {
    NAME = "Adrien"
  }
  tools{maven 'maven'}
  stages{
    stage("Hello"){
      steps{
        echo "hello ${env.NAME}"
      }
    }
  }
}