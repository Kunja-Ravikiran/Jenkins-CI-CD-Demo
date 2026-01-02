pipeline {
    agent any

    stages {
        stage('Build Docker Image') {
            steps {
                sh 'docker build -t jenkins-demo:1.0 .'
            }
        }

        stage('Run Container') {
            steps {
                sh '''
                docker rm -f jenkins-demo-container || true
                docker run -d -p 8081:80 --name jenkins-demo-container jenkins-demo:1.0
                '''
            }
        }
    }
}
