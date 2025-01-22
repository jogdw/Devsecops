
pipeline {
    agent none
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
