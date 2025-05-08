pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                sh 'echo "hello from jenkins"'
                sh 'echo "USER:" && whoami'
                sh 'uname -a'
                sh 'pwd'
            }
        }
    }
}
