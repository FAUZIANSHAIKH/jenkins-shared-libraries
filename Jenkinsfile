pipeline{
    agent any
    tools {
        maven 'maven3'
    }
    stages {
        stage('Build'){
            steps{
                // sh script: 'mvn clean package'
                echo "this Build stage is completed"
            }
        },
        stage('Sonar'){
            steps{
                // sh script: 'mvn clean package'
                echo "this Sonar stage is completed"
            }
        },
        stage('Image Push'){
            steps{
                // sh script: 'mvn clean package'
                echo "this Image Push stage is completed"
            }
        },
        stage('BDD'){
            steps{
                // sh script: 'mvn clean package'
                echo "this BDD stage is completed"
            }
        },
        stage('Nexus Publish'){
            steps{
                // sh script: 'mvn clean package'
                echo "this Nexus Publish stage is completed"
            }
        }
    }
}