pipeline {
    agent any

    stages {

        stage('Clone Repository') {
            steps {
                echo 'Repository cloned successfully'
            }
        }

        stage('Compile Java') {
            steps {
                sh 'javac helloworld.java'
            }
        }

        stage('Execute Java') {
            steps {
                sh 'java Main'
            }
        }
    }
}
