pipeline {
    agent any
    }
    stages {
        stage('mong connect') {
            node('census && docker') {
                docker.image('mongo:2').withRun('-p 27017:27017') { container ->
                withEnv(customEnv) {
                        sh "mongo --version"
                 }
    }

    /* .. */
}
//             steps {
//                 sh 'mongo --version'
//             }
        }
    }
}
