pipeline {
    agent any

    stages {
        stage('PULL') {
            steps {
                sh "git pull https://github.com/LokendraBhat/node_app_automation.git";
            }
        }
        stage("BUILD"){
            steps{
                sh "docker build -t node-app:v3.0 .";
            }
        }
        stage("RUNNING"){
            steps{
                sh "docker compose up -d"
        }
    }
}
