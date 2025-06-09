pipeline {
    agent any
    stages {
        stage('Clone Repository') {
            steps {
                git 'https://github.com/your-username/sample-ci-demo.git'
            }
        }
        stage('Build') {
            steps {
                echo 'Build step...'
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
                sh 'python3 hello.py'
            }
        }
    }
}
