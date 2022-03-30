<<<<<<< HEAD
pipeline{
    agent{
        docker {image 'node:16.13.1-alpine'}
    }
    stages {
        stage('Test') {
            step {
                sh 'node --version'
=======
pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                echo "teste de buid"
            }
        }
        stage('Test') { 
            steps {
                echo "teste na stage de test"
            }
        }
        stage('Deploy') { 
            steps {
                echo " na stage deploy"
>>>>>>> 93625292721ceed8165f95427eab9b7f41974296
            }
        }
    }
}
