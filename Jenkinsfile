pipeline {
    agent any
    stages {
        stage('Example') {
            steps {
                echo 'JOB 1'
            }
        }
        
         stage('Example2') {
            steps {
                echo 'JOB 2'
            }
        }
    }
    post { 
        always { 
            echo ' HAI ONCE AGAIN THIS IS JOB 2!'
        }
    }
}
