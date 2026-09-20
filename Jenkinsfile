pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building flipkart'
                sh 'echo Build completed successfully'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing flipkart'
                sh 'echo Test completed successfully'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying flipkart'
                sh 'echo Deployment completed successfully'
            }
        }
    }

    post {
        success {
            echo 'Pipeline completed successfully'
        }

        failure {
            echo 'Pipeline failed'
        }
    }
}