pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo "OZMAN Reinvent Yourself"
                sh 'echo using shell within Jenkinsfile'
                echo 'Not using shell in the Jenkinsfile'
            }
        }
        stage ('run') {
            steps {
                echo 'Application works'
                sh 'python3 --version'
                sh 'python3 pipeline.py'
            }
        }
    }
}
