pipeline {
  agent any

  stages {
      stage('Build Artifact') {
            steps {
              sh "mvn clean compile -DskipTests=true" //compile
              //archive 'target/*.jar' //so that they can be downloaded later
            }
        }   
    }
}