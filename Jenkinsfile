//Declarative
pipeline {
    agent {docker {image 'maven:latest'}}
    stages {
        stage('Build'){
            steps {
                sh 'mvn --version'
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