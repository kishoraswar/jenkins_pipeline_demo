pipeline {
    agent any

    stages {
        stage('Code Checkout') {
            steps {
                echo 'Checkout git code'
            }
        }
        stage('Build') {
            steps {
                echo 'Build project'
            }
        }
        stage('Test') {
            steps {
                echo 'Junit test case execution'
            }
        }
        stage('Deploy to Dev') {
            steps {
                echo 'Dev deplyoment'
            }
        }
        stage('Deploy To UAT') {
            steps {
                echo 'Deploy to UAT'
            }
        }
        stage('Deploy to PROD') {
            steps {
                echo 'Deplyo t PROD'
            }
        }
    }
}
