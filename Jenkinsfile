pipeline {
    agent any
    stages {
        stage('checkout') {
            steps {
git 'https://github.com/mohammadazeez963/javaProject.git'
            }
        }

    
        stage('compile') {
            steps {
                echo 'compiling'
            }
        }
        stage('Run') {
            steps {
                echo 'Running'
            }
        }
             stage('Test Report using jacoco') {
            steps {
                echo 'jacoco'
            }
        }
          stage('Building Docker Image') {
            steps {
                echo 'Building Docker Image'
            }
        }
    }
}
