pipeline {
    agent any 

    stages {
        stage('git Checkout') {
            steps {
              script {
                git branch: 'main', url: 'https://github.com/harikrishnaB18/devops-java-app.git'
            }
        }
        }
    }
}