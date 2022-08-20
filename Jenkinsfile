pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'javac CidadeTest.java'
            }
        }
        stage('Run') {
            steps {
                sh 'java BubbleSort'
            }
        }
    }
}


