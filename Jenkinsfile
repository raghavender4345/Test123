pipeline {
agent any
    stages {
        stage(Build')
            steps {
               sh 'make'
               }
          }
         stage ('Test'){
              steps {
                 sh 'make checck'
                 }
              }
         stage ('eploy') {
             steps {
                  sh 'make publish'
              }
              }
                
          
               
               
