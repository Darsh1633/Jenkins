pipeline {
    agent any

    stages {
        stage('Fetch Code') {
            steps {
                checkout scm
                echo 'Successfully pulled code from GitHub!'
            }
        }
        
        stage('Build & Deploy') {
            steps {
                echo 'Building application...'
                echo 'Deploying application...'
            }
        }
    }
}
