pipeline {
    agent any
    
    stages {
        stage('version') {
            steps {
                sh 'python3 --version' // Check Python version
            }
        }
        stage('output') {
            steps {
                sh 'python3 test.py' // Run your tests here if available
            }
        }
    }
}
