@Library('my-shared-library') _

pipeline {
    agent any 

    stages{
        stage('git Checkout'){
            steps{
              gitcheckout{
                 branch: "main",
                 url: "https://github.com/harikrishnaB18/devops-java-app.git"
              }
            
            }
        }
    }
 }
