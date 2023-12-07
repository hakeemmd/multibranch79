
pipeline {   
    agent any

    stages {   
        stage('sprint1 branch') { 
            steps { 
               sh 'echo "This is sprint1 branch"' 
            }
        }
     
        stage('Test') { 
            steps { 
               sh 'echo "Test application..."'
            }
        }

        stage("Deploy application") { 
             steps { 
                sh 'echo "Deploying application..."'
            }
        }  
    }
}
