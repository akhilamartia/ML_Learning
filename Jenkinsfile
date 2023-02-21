pipeline {
    agent {
        docker {
            image 'mongo'
        }
    }
    stages {
        stage('build') {
            steps {
                sh 'mongo /home/akhilamartia/mongo_shell/ex1.js'
            }
        }
    }
}
