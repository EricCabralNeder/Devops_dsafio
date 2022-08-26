pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'mvn clean install -DskipTests'
            }
        }
        stage('Test') {
            steps {
                echo 'mvn test'
            }
        }
    }
}


