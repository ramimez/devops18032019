pipeline { 
agent any  
stages {
         stage("Prepare Wevioo"){ 
       steps{
         sh '''
           echo "Prepare continuous delivery env"
           '''
         } 
     }

     stage ("Build"){
       steps {
         sh '''
           echo "Building app"
         '''
           bat(/"${mvnHome}\bin\mvn" -Dmaven.test.failure.ignore clean install/)       
       }
     }
}
}        
