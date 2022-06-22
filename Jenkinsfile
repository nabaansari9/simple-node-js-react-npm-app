pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
                echo 'Building the application'
                nodejs ('Node-18.4'){
                    sh 'npm install -g npm@8.12.2'
                }
                 
            }
        }
        stage('Test') { 
            steps {
                echo 'Testing the application'
            }
        }
        stage('Deploy') { 
            steps {
                echo 'Deploying the application'
            }
        }
    }
}