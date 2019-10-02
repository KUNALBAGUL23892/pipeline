pipeline {
         agent any
         stages {
                 stage('git step') {
                 steps {
                     echo 'Hi, this is MY GIT STEP'
                    sh 'git --version'
                 }
                 }
                 stage('maven step') {
                 steps {
                    input('this is my maven step')
                  sh 'mvn --version' 
                 }
                 }
                 stage('Transfer of jar to server') {
                 steps {
                    sh 'touch a.jar'
                    sh 'cp a.jar /tmp'
                            
                       }
      
                              
                           
                           }
                           }
              }
