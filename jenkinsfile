pipeline {
    agent any
    stages {
        stage('Fetch') {
            steps {
                sh 'echo Fetch'
            }
        }
        stage('Test') {
            steps {
                sh 'echo Test'
            }
        }
        stage('Build') {
            input{
                message 'do you want to continue'
            }
            steps {
                sh 'echo Build'
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo Deploy'
            }
        }
    }
}
