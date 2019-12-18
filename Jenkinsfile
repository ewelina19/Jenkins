pipeline {
    agent any
    stages {
        stage('Test') {
            
            parallel {
                stage('Performance test') {
                    steps { 
                        echo "Perfrmance test"
                    }
                }
                stage('Smoke test') {
                    steps { 
                        echo "Smoke test"
                    }
                }
            }
        }
        stage('Build') {
            steps {
                echo "Build"
            }
        }
        stage('Deploy (Staging)') {
            steps {
                echo "Deploy (Staging"
            }
        }
        stage('Manual Approval') {
            steps {
                echo "Deploy (Staging"
            }
        }
        stage('Deploy (Production)') {
            steps {
                echo "Deploy (Production)"
            }
        }   
    }
}
