pipeline {
   agent any
   stages {
      stage('Build_source'){
         steps {
           echo 'Running Build stage'
           sh './gradlew build --no-daemon '
           archiveArtifacts artifacts: 'dist/trainSchedule.zip'
           }
   
   
   }


}
