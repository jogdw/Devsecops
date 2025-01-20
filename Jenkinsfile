
pipeline {
    agent any

    tools {
        maven 'Maven'
    }
    
    stages {
        stage("build") {
            steps {
                echo 'Building the application'
            }
        }
        stage("test") {
            steps {
                sh 'mvn -v'
            }
        }
        stage("deploy") {
            steps {
                echo 'Deploying the application'
            }
        }
    }
}
