pipeline{
  agent any{
    stages{
      stage('Build'){
        steps{
            echo 'My first jenkins pipeline'
            sh './gradlew build --no-daemon'
            archiveArtifacts artifacts: 'dist/trainSchedule.zip'
        }
      }
    }
  }
}
