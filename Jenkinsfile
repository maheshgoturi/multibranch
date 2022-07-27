pipeline {
    agent any 
    stages {
        stage('List env vars') {
            steps {
                script {
                    echo "Running checkout"
                    gitScmVars = checkout scm
                    echo "Running checkout complete"
                    echo "$gitScmVars"
                }
            }
        }

    }
}
