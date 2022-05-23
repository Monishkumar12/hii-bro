pipeline {
    agent any

    stages {
        stage('compile') {
            steps {
                sh 'mvn compile'
            }
        }
        stage('test') {
            steps {
                echo 'Hello World1'
            }
        }
        stage('build') {
            steps {
                echo 'Hello World2'
            }
        }
        
    }
}
