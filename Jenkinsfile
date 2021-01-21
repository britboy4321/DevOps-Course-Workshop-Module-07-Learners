pipeline {
    agent any 
    stages {
        stage('Stage 1') {
            agent{
                docker{image 'mcr.microsoft.com/dotnet/core/sdk:3.1'}
            }
            steps {
                echo 'Hello world 2!' 
                sh 'dotnet build'
            }
        }
    }
}