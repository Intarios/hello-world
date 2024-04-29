pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Build success'
                //check node version
                sh 'node -v'
            }
        }
        stage('Test') {
            steps {
                echo 'Test success'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploy success'
            }
        }
        stage('Clean up') {
            steps {
                echo 'Clean up success'
            }
        }

    }
}