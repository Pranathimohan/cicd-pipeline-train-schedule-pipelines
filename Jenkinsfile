pipeline {
  agent any
  stages {
    stage ('Build') {
       steps {
         echo 'Running build automaation'
         sh'./gradlew build --no-deamon'
         archiveArtifacts: 'dist/trainSchedule.zip'
      } 
    }
  } 
}
