pipeline {   
    agent any

    stages {   
        stage('deploy branch updated') { 
            steps { 
               sh 'echo "This is deploy branch"' 
            }
        }
     
        stage('sprint1') { 
            steps { 
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
