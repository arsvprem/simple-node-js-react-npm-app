pipeline {
    agent {
        docker {
            image 'node:12-alpine'
            args '--dns 10.65.160.28 -p 3000:3000'
        }
    }
    stages {
        stage('Build') {
            steps {
                sh 'npm install'
            }
        }
    }
}
