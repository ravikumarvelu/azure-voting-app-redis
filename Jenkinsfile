pipeline {
    agent any

    stages {
        stage('Verify Branch') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Docker Build') {
            steps {
                sh 'docker compose build'
            }
        }
    }
}
