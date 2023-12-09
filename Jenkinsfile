
pipeline {   
    agent any

    stages {   
        stage('sprint1 branch updated') { 
            steps { 
               sh 'echo "This is sprint1 branch updated"' 
            }
        }
     
        stage('sprint1') { 
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
