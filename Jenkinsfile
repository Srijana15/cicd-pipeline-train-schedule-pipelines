pipeline {
  agent any
  stages ('Build') {
    steps {
      echo 'Running build automation'
      sh './gradlew build --n0-daemon'
      archiveArtifacts artifacts: 'dist/trainSchedule.zip'
    }
    }
  }
}
    
