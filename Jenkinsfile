pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Checkout..'
            }
        }
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('SonarAnalysis') {
            steps {
                echo 'Code and security scanning....'
            }
        }
	stage('Deploy in Prod environment') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}

