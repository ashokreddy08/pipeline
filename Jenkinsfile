pipeline {
    agent any
    tools  {
        maven 'maven'
        jdk 'jdk'
    }
    stages {
        stage ('Compile Stage') {
            steps {
                sh 'mvn compile'
                }
              }
       stage ('Testing Stage') {
            steps {
                sh 'mvn test'
                }
             }
       stage ('Deployment Stage') {
            steps {
                sh 'mvn deploy'
                }
           }
      }
}
