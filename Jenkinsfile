pipeline {
    agent any
    tools  {
        maven 'Maven'
    }
    stages {
        stage ('Compile Stage') {

            steps {
                
                    bat 'mvn compile'
                
            }
        }

        stage ('Testing Stage') {

            steps {
                
                    bat 'mvn test'
                
            }
        }


        stage ('Deployment Stage') {
            steps {
                
                    bat 'mvn deploy'
                
            }
        }
    }
}
