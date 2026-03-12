pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo 'Building project from GitHub...'
            }
        }

        stage('Test') {
            steps {
                echo 'Running automated tests...'
            }
        }

        stage('Integration') {
            steps {
                echo 'Integrating code changes...'
            }
        }

        stage('Success') {
            steps {
                echo 'CI Pipeline executed successfully!'
            }
        }

    }
}
