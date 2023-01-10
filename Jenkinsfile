pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'pwd'
                sh 'ls -lah'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
