pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo "updated"
                sh 'echo using shell within Jenkinsfile'
                echo 'not using shell in the Jenkinsfile'
            }
        }
    }
}