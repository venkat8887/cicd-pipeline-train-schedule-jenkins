pipleline {
  agent any 
  stage {
  
    stage {"Build"} {
       steps {
       
       echo " running build auto"
       sh './gradlew build --no-daemon' 
       ArchiveArtifacts 'dist/trainSchedule.zip' 
       }
    
    
    }
  
   }
  }
