//Declarative
pipeline {
    agent {docker {image 'maven:3-jdk-8'}}
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