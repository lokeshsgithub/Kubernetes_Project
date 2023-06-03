pipeline {

    agent any

    stages{

        stage('Checkoutcode'){

            steps{
                git credentialsId: 'github_auth', url: 'https://github.com/lokeshsgithub/Kubernetes_Project.git'
            }
        }
    }
}