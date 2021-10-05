pipeline{
    agent any
    stages{
        stage("Git Checkout"){
            steps{
                git branch: 'main', credentialsId: 'TestGit', url: 'https://github.com/korona2020/firstjob.git'
            }
        }
    }
}
