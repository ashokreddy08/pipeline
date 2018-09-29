pipeline {
    agent any
    tools  {
        maven 'Maven'
    }
    stages {
        stage ('Compile Stage') {

            steps {
                echo "this is compile stage"
                    sh 'mvn compile'
                
            }
        }

        stage ('Testing Stage') {

            steps {
                echo "This is testing stage"
                    sh 'mvn test'
                
            }
        }


        stage ('Deployment Stage') {
            steps {
                echo " This is deployment"
                    sh 'mvn deploy'
                
            }
        }
    }
}
