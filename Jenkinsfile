pipeline {
    agent any

    stages {
        stage('compile') {
            steps {
                bat 'mvn compile'
            }
        }
        stage('testing') {
            steps {
                bat 'mvn testing'
            }
        }
        stage('build') {
            steps {
                echo 'Hello World2'
            }
        }
        
    }
}
