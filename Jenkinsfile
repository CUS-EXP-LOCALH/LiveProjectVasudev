pipeline {
    agent any
    stages {
        stage('Example') {
            steps {
                echo 'JOB 2'
            }
        }
    }
    post { 
        always { 
            echo 'ONCE AGAIN THIS IS JOB 2!'
        }
    }
}
