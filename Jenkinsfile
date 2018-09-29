pipeline {
    agent any
    tools  {
        maven 'Maven'
    }
    stages {
        stage ('Compile Stage') {

            steps {
                script
                {
                
                echo "this is compile stage"
                    sh 'mvn compile'
                    echo " This is after compile"
                }
            }
        }

        stage ('Testing Stage') {

            steps {
                 script
                {
                
                    echo "This is testing stage"
                    sh 'mvn test'
                    echo "This is test"
                }
            }
        }


        stage ('Deployment Stage') {
            steps {
                script
                {
                echo " This is deployment"
                    sh 'mvn deploy'
                    
                }
            }
        }
    }
}
