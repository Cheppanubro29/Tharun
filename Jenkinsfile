pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/Cheppanubro29/Tharun.git'
            }
        }

        stage('Run Python Script') {
            steps {
                sh 'python3 jenkins_hello.py'
            }
        }
    }
}
