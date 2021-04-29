pipeline {
 agent any
 tools {
    maven 'M2_HOME'
 }
 stages {
   stage('Build'){
     steps {
     sh 'mvn clean'
     sh 'mvn install'
     sh 'mvn package'
       sleep 10
     }
   }
  stage('Steve'){
     steps {
     echo "AFAMEFUNA"
     sh 'mvn test'
     }
   }
  stage('Chigom'){
     steps {
     echo "Chigom"
       sleep 10
     }
   }
  stage('Chigozieafam'){
     steps {
     echo "Chimaafam"
       sleep 10
     }
   }
 }
}
