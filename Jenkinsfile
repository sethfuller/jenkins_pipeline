#!groovy

pipeline {
    agent any
    stages {
        stage('Stage 1') {
            steps {
                echo 'Step 1'
                echo 'Step 1A'
            }
        }
        stage('Stage 2') {
            steps {
                echo 'Step 2'
                sh "pwd"
            }
        }
        stage('Stage 3') {
            steps {
                sh "ls -lF .."
                echo 'Step 3'
            }
        }
        stage('Stage 4') {
            steps {
                sh "ls -lF /"
                echo 'Step 4'
            }
        }
        stage('Stage 5') {
            steps {
                sh "ls -lF /bin"
                echo 'Step 5'
            }
        }
        stage('Stage 6') {
            steps {
                sh "java -version"
                echo 'Step 6'
            }
        }
    }
}
