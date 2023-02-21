pipeline {
    agent {
        docker{
            image 'mongo'
            -p 8080:8080
        }
    }
    stages {
        stage('mong connect') {
            steps {
                sh 'mongo --version'
            }
        }
    }
}
