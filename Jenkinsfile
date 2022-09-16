pipeline {
    agent { dockerfile true }
    stages {
        stage('Test') {
            steps {
                echo 'hello world!'
                sh 'python test.py'
            }
        }
    }
}
