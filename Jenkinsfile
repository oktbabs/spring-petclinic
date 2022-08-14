pipeline {
    agent any
      environment {
                           DOCKER_HOME='/usr/bin/docker'
      }
       
 
 
    stages {   
      
    stage('git clone repo') {
            steps {
                git branch: 'main', credentialsId: 'oktbabs', url: 'https://github.com/oktbabs/spring-petclinic.git'

            }
        } 
    }
 }
