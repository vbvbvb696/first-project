pipeline {
    agent any 
    
stages { 
     
 stage('Preparation') { 
     steps {
// for display purpose

      // Get some code from a GitHub repository

      //git 'https://github.com/raknas999/game-of-life.git'
      git 'https://github.com/vbvbvb696/first-project.git'

      // Get the Maven tool.
     
 // ** NOTE: This 'M3' Maven tool must be configured
 
     // **       in the global configuration.   
     }
   }

   stage('Build') {
       steps {
       // Run the maven build

      //if (isUnix()) {
         sh './hello.sh'
      //} 
      //else {
      //   bat(/"${mvnHome}\bin\mvn" -Dmaven.test.failure.ignore clean package/)
       }
//}
   }
 
  
 }
     
}



