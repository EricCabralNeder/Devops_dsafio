pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                 echo "Pipeline Usando Jenkinsfile"
            }
        }
        stage('Run') {
            steps {
               sh 'mvn source:jar'
            }
        }
    }
}


