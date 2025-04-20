pipeline{
    agent {
        docker {
            image 'node:18'
        }
    }
    stages{
        stage('Run index.js') {
            steps {
                sh 'node index.js'
            }
        }
    }
}