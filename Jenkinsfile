pipeline {
    agent any
    stages {
        stage("Get the Source") {
            steps {
                sh 'echo "Getting source code"'
            }

        }

        stage("Build") {
            steps {
                sh 'echo "Building code with maven"'
            }
        }

        stage("Test") {
            steps {
                sh 'echo "testing code with sonar"'
            }
        }

        stage("Deploy") {
            steps {
                sh 'echo "Deploying code to dev"'
            }
        }
    }
}