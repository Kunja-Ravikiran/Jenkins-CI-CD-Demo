pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo "Hello, Jenkins! Pipeline is working."
            }
        }

        stage('Docker Version Check') {
            steps {
                sh 'docker --version'
            }
        }
    }
}

