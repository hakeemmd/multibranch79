pipeline {   
    agent any

    stages {   
        stage('Deploy branch update') { 
            steps { 
               sh 'echo "This is Deploy branch update"' 
            }
        }
     
        stage('sprint1') { 
            steps 
	    { 
               sh 'echo "sprint1 application..."'
            }
        }

        stage("Deploy application") { 
             steps { 
                sh 'echo "Deploying application..."'
            }
        }  
    }
}
