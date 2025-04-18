pipeline {
    agent any
    stages {
        stage("Get the Source") {
            steps {
                sh echo "Getting source code"
            }

        }

        stage("Build") {
            steps {
                sh echo "Building code"
            }
        }

        stage("Test") {
            steps {
                sh echo "testing code"
            }
        }

        stage("Deploy") {
            steps {
                sh echo "Deploying code to dev"
            }
        }
    }
}