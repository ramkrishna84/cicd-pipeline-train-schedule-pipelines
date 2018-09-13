pipeline{
 agent any
 stages{
  stage('build') {
   step {
    sh './gradlew build --no-deamon'
    archiveArtifacts artifacts: 'dist/trainSchedule.zip'
    }
  }
 }
}
