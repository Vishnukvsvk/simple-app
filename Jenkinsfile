pipeline {
    agent any //Master or slave
    tools{
        maven 'maven3'
    }
    stages{
        stage('Build'){
            steps{
                sh script: 'mvn clean package'
            }
        }
    }
}