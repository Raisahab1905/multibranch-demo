pipeline {
    agent any
    stages {
        stage('Hotfix Build') {
            steps {
                echo "Building hotfix-crash branch"
            }
        }
        stage('Quick Test') {
            steps {
                echo "Running minimal tests for hotfix"
            }
        }
    }
}
