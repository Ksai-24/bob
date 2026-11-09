pipeline {
    agent any

    stages {

        stage('BUILD' ) {
            steps {
                echo 'Repository cloned successfully'
            }
        }

        stage('TEST') {
            steps {
                sh 'javac hello.java'
            }
        }

        stage('DEPLOY') {
            steps {
                sh 'java Main'
            }
        }
    }
}
