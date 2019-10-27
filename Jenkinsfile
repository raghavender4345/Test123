pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
               sh 'make'
           }
        }
        stage ('Test'){
            steps {
                 sh 'make checck'
                  junit 'report/**/*.xml'
            }
         }
         stage ('Deploy') {
             steps {
                  sh 'make publish'
              }
         }
     }            
}        
               
               
