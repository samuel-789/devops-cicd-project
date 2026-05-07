pipeline {
    agent any

    stages {

        stage('GitHub Checkout') {
            steps {
                echo 'Code pulled from GitHub'
            }
        }

        stage('Build Maven Project') {
            steps {
                sh 'mvn clean package -DskipTests'
            }
        }

    }
}
