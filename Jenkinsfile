//Declarative
pipeline {
    agent {docker {image 'maven:3.6.3'}}
    stages {
        stage('Build'){
            steps {
            
                echo "Build stage"
            }
        }
        stage('UAT'){
            steps {
                echo "UAT stage"
            }
        }
        stage('Integration'){
            steps {
                echo "Integration stage"
            }
        }
    }
}