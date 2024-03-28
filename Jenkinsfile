pipeline {   
    agent any

    stages {   
        stage('main') { 
            steps { 
               sh 'echo "This is master branch"' 
            }
        }
     
        stage('sprint1') { 
            steps { 
               sh 'echo "sprint1 application..."'
            }
        }

        stage('sprint2') { 
             steps { 
                sh 'echo "sprint2 application..."'
            }
        }  
    }
}
