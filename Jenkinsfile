pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'javac DecideTest.java'
            }
        }
        stage('Run') {
            steps {
               echo "Pipeline Usando Jenkinsfile"
            }
        }
    }
}


