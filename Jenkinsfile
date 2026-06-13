pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo 'Building Application'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing Application'
            }
        }

        stage('Docker Build') {
    steps {
        sh 'docker build -t cicd-app .'
    }
}

        stage('Deploy') {
            steps {
                echo 'Deploying Application'
            }
        }
    }
}