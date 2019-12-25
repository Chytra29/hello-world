pipeline{
 agent any
 stages{
   stage('building the application') {
    tools {
        maven 'maven3'
    }
     steps{ 
       echo "Welcome to Jenkins peipeline"
        sh "hostname"
        sh "git --version"
      echo ${maven}
        sh "${maven}/bin/mvn --version"
             }
         }
        }
}
