pipeline{
 agent any
 stages{
  stage('build') {
   steps {
    sh './gradlew build'
    archiveArtifacts artifacts: 'dist/trainSchedule.zip'
    }
  }
 }
}
