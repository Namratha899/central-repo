pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git url: 'https://github.com/your-username/your-repo.git'
            }
        }

        stage('Build') {
            steps {
                echo "Building the application"
                
            }
        }

        stage('Tet') {
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
