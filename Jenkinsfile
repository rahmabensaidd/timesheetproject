pipeline {

 agent any

    tools {
        jdk 'JDK17'
        maven 'Maven3'
    }

 stages {

 stage('GIT') {

           steps {

               git branch: 'main',

               url: ' https://github.com/rahmabensaidd/timesheetproject.git'

          }

     }

 stage ('Compile Stage') {

 steps {

 sh 'mvn clean compile'

 }

 }

 }

}