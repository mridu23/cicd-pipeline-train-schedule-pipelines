pipeline {
  agent any
  stages {
    stage ('Build')
      { steps {
        echo 'Running buildi automation'
        sh './gradlew build --no-daemon'
        archiveArtifacts artifcats: 'dist/trainSchedule.zip'
      }
      }
  }
}
