pipeline {
    agent any

    stages {

        stage('Git Checkout') {
            steps {

                echo "Cloning Repository..."

                git branch: 'main',
                url: 'https://github.com/vikasrajput0112/test-repo-19may.git'
            }
        }

        stage('Build') {
            steps {

                echo "Building Application..."

                sh 'echo Build Started'
            }
        }

        stage('Test') {
            steps {

                echo "Running Tests..."

                sh 'echo Test Execution Started'
            }
        }

        stage('Deploy') {
            steps {

                echo "Deploying Application..."

                sh 'echo Deployment Started'
            }
        }
    }
}
