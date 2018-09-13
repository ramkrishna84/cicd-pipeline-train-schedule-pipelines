pipeline{
 agent any
 stages{
  stage('build') {
    sh './gradlew build --no-deamon'
    archiveArtifacts artifacts: 'dist/trainSchedule.zip'
   }
 }
}
