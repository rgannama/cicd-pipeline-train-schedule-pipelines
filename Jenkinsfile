pipeline{
  agent any
  stages{
    stage('Build'){
    echo 'Running build automation'
    sh './gradlew buil --no-daemon'
    archiveArtifacts artifacts: 'dist/trainschedule.zip'
   }
  } 
 }
} 
