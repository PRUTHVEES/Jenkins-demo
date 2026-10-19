
pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git 'https://github.com/PRUTHVEES/Jenkins-demo.git'
            }
        }

        stage('Build') {
            steps {
                bat 'python app.py'
            }
        }

        stage('Test') {
            steps {
                bat 'python test.py'
            }
        }
    }
}
