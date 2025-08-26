pipeline{
    agent any
    triggers { 
        pollSCM('* * * * *') 
        }
    stages{
        stage('Welcome message'){
            steps{
                echo 'Welcome to Jenkinsfile'
            }
        }
    }
}