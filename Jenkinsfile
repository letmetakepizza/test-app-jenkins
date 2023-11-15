pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                sh "whoami"
                sh "pwd"
                sh "ls -la"
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
                sh "curl -4 ifconfig.me"
                echo "string 3"
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
                echo "just echo"
                echo "string 344433"
            }
        }
    }
}
