pipeline {
         agent any
         stages {
                 stage('git step') {
                 steps {
                     echo 'Hi, this is MY GIT STEP'
                    sh git --version
                 }
                 }
                 stage('maven step') {
                 steps {
                    input('this is my maven step')
                    mvn --version 
                 }
                 }
                 stage('Transfer of jar to server') {
                 steps {
                       touch a.jar
                       cp a.jar /tmp
                            
                       }
      
                              
                           }
                           }
                           }
              }
