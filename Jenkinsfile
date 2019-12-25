pipeline{
 agent any
 tools {
        maven 'maven3'
    }
 stages{
   stage('building the application') {
    
     steps{ 
      sh "mvn clean install"
             }
         }
        }
}
