pipeline {
    agent any

    stages {

        stage('Start') {
            steps {
                echo "Pipeline started successfully"
            }
        }

        stage('Hello World') {
            steps {
                echo "Hello World from Jenkins"
            }
        }

        stage('Test Command') {
            steps {
                sh 'echo This is a test pipeline'
                sh 'date'
                sh 'whoami'
            }
        }

        stage('Finish') {
            steps {
                echo "Pipeline finished successfully"
            }
        }

    }
}
