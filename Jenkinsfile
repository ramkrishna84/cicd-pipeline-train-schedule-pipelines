pipeline{
 agent any
 stages{
  stage('build') {
   steps {
    sh './gradlew build --no-deamon'
    archiveArtifacts artifacts: 'dist/trainSchedule.zip'
    }
  }
 }
}
