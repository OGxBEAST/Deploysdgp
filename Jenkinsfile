pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                // Define build steps here
                echo 'Building...'
            }
        }
        stage('Test') {
            steps {
                // Define test steps here
                echo 'Testing...'
            }
        }
        stage('Deploy') {
            when {
                // Specify to deploy only if changes are pushed to the main branch
                branch 'main'
            }
            steps {
                // Define deployment steps here
                echo 'Deploying...'
            }
        }
    }
}