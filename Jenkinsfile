pipeline {
    agent any
    parameters {
        choice(name: 'ENVIRONMENT', choices: ['dev', 'prod'], description: 'Select environment')
        string(name: 'VERSION', defaultValue: '1.0.0', description: 'Application version')
    }

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/Namratha899/central-repo.git'
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

