pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
              sh 'echo "This is from build stage"'
            }
        }
        stage('Test') {
            steps {
                sh 'echo "This is from test stage"'
            }
        }
        stage('Deploy') {
            steps {
             sh 'echo "This is from deploy stage"'
            }
        }
    }
}