pipeline {
    agent any 


    stages {
        stage('Dependencies') {
            steps {
                echo 'Fetching dependencies...'
                
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
               
            }
        }

        stage('Build') {
            steps {
                echo 'Building the binary...'
                
            }
        }

 
         


       
        }

        
    }

    post {
        always {
            echo 'This will always run'
        }
        success {
            echo 'Pipeline completed successfully!'
        }
        failure {
            echo 'Pipeline failed :('
        }
    }
}
