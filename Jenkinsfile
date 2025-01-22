
pipeline {
    agent none

    tools {
        maven 'Maven'
    }
        
    stages {
        stage("Build & Analyse") {
            agent any
            steps {
                script {
                    sh 'mvn clean package sonar:sonar'
                }
            }
        }
    }
}
