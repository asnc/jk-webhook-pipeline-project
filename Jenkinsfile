pipeline {
    agent any
    stages {
        stage('run') {
            steps {
                echo 'Integrating Jenkins Pipeline with GitHub Webhook using Jenkinsfile'
                sh 'python3 --version'
                sh 'python3 pipeline.py'
            }
        }
    }
}
