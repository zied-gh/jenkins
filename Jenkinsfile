pipeline {

 agent any

  tools {
         jdk 'JAVA_HOME'
         maven 'M2_HOME'
     }

 stages {

 stage('GIT') {

           steps {

               git branch: 'master',

               url: 'https://github.com/zied-gh/jenkins'

          }

     }

 stage ('Compile Stage') {

 steps {

 sh 'mvn clean compile'

 }

 }

 }

}

