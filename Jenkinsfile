  
pipeline {
    agent {
        docker {
            image 'maven:3.3.3-alpine'
            args '-v /root/.m3:/root/.m3'}
                steps
        {
               echo 'hello Maven'
                sh 'mav --version'
        }
    }
        }
    }
