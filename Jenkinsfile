pipeline {   
    agent any

    stages {   
        stage('Deploy branch') { 
            steps { 
               sh 'echo "This is Deploy branch"' 
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
