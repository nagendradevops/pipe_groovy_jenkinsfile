pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building the application...'
                // Insert build steps here (e.g., compile code, run tests)
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
                // Insert test execution steps here
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying the application...'
                // Insert deployment steps here (e.g., deploy to a server)
            }
        }
    }

    post {
        success {
            echo 'Pipeline executed successfully!'
        }
        failure {
            echo 'Pipeline failed!'
        }
    }
}

