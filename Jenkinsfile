pipeline {
    agent any
    stages {
        stage('Build') {
            agent{
                docker {image 'maven'}
            }
            steps {
               sh 'mvn source:jar'
            }
        }
    }
}


