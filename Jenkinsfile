pipeline {
    agent any
    stages {
        stage('Example') {
            steps { 
                git credentialsId: 'main', url: 'https://github.com/ASIExpleo/mobile.git'
                echo 'Pipeline Script for testing connection'
            }
        }
    }
}
