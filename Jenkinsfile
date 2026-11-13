pipeline {
    agent any

    stages {

        stage ('checkout') {
            steps {
                echo 'checking out source code'
            }
             
        }

        stage ('Build') {
            steps {
                echo 'preparing files '
                sh 'ls -l'
            }
        }

        stage ('Test') {
            steps {
                echo 'Running test cases'
            }
        }

        stage ('Deploy') {
            steps {
                echo 'deploying an application'
            }
        }
    }
    post {
        success {
            echo 'Deployment is successful'
        }
        failure {
            echo 'Deployment failed'
        }
    }
}
