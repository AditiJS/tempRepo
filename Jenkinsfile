pipeline {
    agent any
    
    stages {
        stage('version') {
            steps {
                sh 'python --version' // Check Python version
            }
        }
        stage('Output') {
            steps {
                sh 'python test.py' // Run your tests here if available
            }
        }
    }
}
