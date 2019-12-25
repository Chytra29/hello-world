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
        sh "mvn3 --version"
             }
         }
        }
}
