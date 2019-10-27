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
         stage ('deploy') {
             steps {
                  sh 'make publish'
              }
              }
                
          
               
               
