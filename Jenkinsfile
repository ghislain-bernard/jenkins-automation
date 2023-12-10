pipeline {
    agent any
    options {
        skipDefaultCheckout()
    }
    stages {
        stage('clean') {
            steps {
                cleanWs()
            }
        }
        stage('clone') {
            steps {
                checkout scm
            }
        }
    }
}
