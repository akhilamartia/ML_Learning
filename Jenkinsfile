pipeline {
    agent {
        docker {
            image 'mongo:2'
            args '-p 27017:27017'
        }
    }
    stages {
        stage('mongo connect') {
            steps {
                sh 'mongo --version'
//             node('census && docker') {
//                 docker.image('mongo:2').withRun('-p 27017:27017') { container ->
//                 withEnv(customEnv) {
//                         sh "mongo --version"
//                  }
//                 }
//             }
            }
        }
    }
        
//             steps {
//                 sh 'mongo --version'
//             }
}
