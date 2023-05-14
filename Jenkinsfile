pipeline {
  agent any
  stages {
    stage ('Build') {
      steps {
        echo 'Running build automation'
        sh './gradlew build --no-daemon'
        archiveArtifacts atrifacts: 'dist/trainSchedule.zip'
      }
    }
  }
}
