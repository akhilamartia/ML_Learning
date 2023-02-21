pipeline {
    agent {
        docker{
            image 'mongo'
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
