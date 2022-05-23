pipeline {
    agent any

    stages {
        stage('compile') {
            steps {
                bat 'mvn compile'
            }
        }
        stage('test') {
            steps {
                sh 'mvn testing'
            }
        }
        stage('build') {
            steps {
                echo 'Hello World2'
            }
        }
        
    }
}
