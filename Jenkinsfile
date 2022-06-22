pipeline {
    agent any
    tools{
        nodejs Node-18.4
    }
    stages {
        stage('Build') { 
            steps {
                echo 'Building the application'
                sh 'npm install' 
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