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
                echo 'Step 3'
                sh "ls -lF .."
            }
        }
        stage('Stage 4') {
            steps {
                echo 'Step 4'
                sh "ls -lF /"
            }
        }
        stage('Stage 5') {
            steps {
                echo 'Step 5'
                sh "ls -lF /bin"
            }
        }
        stage('Stage 6') {
            steps {
                echo 'Step 6'
                sh "java -version"
            }
        }
    }
}
