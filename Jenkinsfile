pipeline {
    agent {
        docker { image 'node:7-alpine' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'ls -al; echo "####"; pwd'
            }
        }
    }
}
