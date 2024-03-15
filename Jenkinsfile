pipeline {   
    agent any

    stages {   
        stage('Master') { 
            steps { 
               sh 'echo "This is master branch"' 
            }
        }
     
        stage('sprint branch and application') { 
            steps { 
               sh 'echo "sprint1 and application..."'
            }
        }

        stage("Development") { 
             steps { 
                sh 'echo "Deploying application..."'
            }
        }  
    }
}
