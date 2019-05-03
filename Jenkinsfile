pipleline {
  agent any 
  stage {
  
    stage {"Build"} {
       steps {
       
       echo " running build auto"
       sh './gradlew build --no-daemon' 
       archiveArtifacts 'dist/trainSchedule.zip' 
       }
    
    
    }
  
   }
  }
