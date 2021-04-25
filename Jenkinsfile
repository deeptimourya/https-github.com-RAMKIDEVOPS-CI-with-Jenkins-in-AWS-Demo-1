pipeline{
  agent any
  stages{
    stage("build"){
      steps{
        
      }
    }
  }
  post {
        always {
            archiveArtifacts artifacts: '**/*.min.*', onlyIfSuccessful: true
        }
    }
}
