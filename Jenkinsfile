pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'ls -lah'
            }
        }
        stage('Publish'){
            steps {
                archiveArtifacts artifacts: '*'
            }
        }
    }
}
