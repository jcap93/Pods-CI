pipeline {
    agent {label 'java8'}
    stages {
        stage("Pre-Deploy Validation"){
            steps{
                echo "This job validates before Production"
            }
        }

        stage("Deploy to Develop Enviornment"){
            steps{
                echo "This job deploys project to dev enviornment"
            }
        }

        stage("Run Test Automation"){
            steps{
                echo "This job iniates Test Automation"
            }
        }
    }
}