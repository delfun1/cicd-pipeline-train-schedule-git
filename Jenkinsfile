pipeline  {
  agent any
  stages ( 'Build') {
    steps {
      echo 'Runing biuld automation'
      sh ' ./gradle build --no-daemon'
      achiveArtifacts artifacts: 'dist/trainSchedule.zip'
    }
  }
}
    
