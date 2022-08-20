pipeline {
    agent {
        docker {
            image 'python'
        }
    }

    stages {
        stage('build') {
            steps {
                sh 'pip install -r requirements.txt'
            }
        }
        stage('API Test') {
            steps {
                sh 'robot -L trace -d ./logs tests/api'
            }
        }
    }
    post {
        always {
            robot 'logs'
            chuckNorris()
        }
    }
}


