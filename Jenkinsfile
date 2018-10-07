pipeline {
    agent any
    tools  {
        maven 'maven'
        jdk 'jdk'
    }
    stages {
        stage ('Compile Stage') {
            steps {
                bat "mvn -B compile"
                }
              }
        stage ('Testing Stage') {
            steps {
                bat "mvn -B test"
                }
             }
        stage ('Deployment Stage') {
            steps {
                bat "mvn -B deploy"
                }
           }
      }
}
