pipeline {   
    agent any

    stages {   
        stage('Master') { 
            steps { 
               sh 'echo "This is master branch"' 
            }
        }
     
        stage('sprint1 branch application') { 
            steps { 
               sh 'echo "sprint1 application..."'
            }
        }

        stage("Development") { 
             steps { 
                sh 'echo "Deploying application..."'
            }
        }  
    }
}
