pipeline {
    agent any

    stages {
        stage('stage1') {
            steps {
                echo "hi stage 1"
                sh "whoami"
            }
        }    
        stage('stage2') {
            steps {
                echo "hello stage 2"
                sh "uname"
                sh "pwd"
            }
        }    
        stage('stage3') {
            steps {
                echo "greetings stage 3"
                sh "ls -la"
                echo "enddd"
            }
        }
    }
}