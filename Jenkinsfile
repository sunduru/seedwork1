pipeline{
  agent any
  stages{
    stage('git clone'){
      steps{
        git url: "https://github.com/sunduru/seedwork", branch: "main"
      }
    }
    stage ('shell script'){
      steps{
        script{
          bat "type README.md"
        }
      }
    }
  }
}
