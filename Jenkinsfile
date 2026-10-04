pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                echo 'Checking out application'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing application'
            }
        }

        stage('Run Application') {
            steps {
                bat 'python app.py'
            }
        }
    }
}
