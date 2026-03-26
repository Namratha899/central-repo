pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git url: 'https://github.com/Namratha899/central-repo.git'
            }
        }

        stage('Build') {
            steps {
                echo "Building the application"
                
            }
        }

        stage('Test') {
            steps {
                echo "Running tests"
               
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploying application"
               
            }
        }
    }
}

