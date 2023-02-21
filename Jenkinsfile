pipeline {
    agent {
        docker{
            image 'mongo:2'
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
