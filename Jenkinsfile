pipeline {
    agent any
    
    stages {
        stage('GitJob') {
            steps {
                echo 'Checking out source code from GIT'
            }
        }
        stage('Build') {
            steps {
                echo 'Docker image is getting built'
            }
        }
        stage('Push') {
            steps {
                echo 'Docker image is getting pushed to docker hub'
            }
        }
    }
}
