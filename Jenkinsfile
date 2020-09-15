pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Build stage'
            }
        }
        stage('Test') { 
            steps {
                bat 'mvn clean' 
            }
        }
        stage('Clean') { 
            steps {
                bat 'Clean stage' 
            }
        }           
        
    }
}
