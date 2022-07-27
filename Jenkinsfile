pipeline {
    agent any 
    stages {
        stage('List env vars') {
            steps {
                script {
                    echo "Running checkout"
                    checkout scm
                    echo "Running checkout complete"
                }
            }
        }

    }
}
