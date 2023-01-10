pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                pwd
                ls -lah
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
