node {

    stage('BUILD') {
        echo "Building Java Application..."
        checkout scm
        sh 'javac Main.java'
        echo "Build Completed Successfully"
    }

    stage('TEST') {
        echo "Testing Java Application..."
        sh 'java Main'
        echo "Testing Completed Successfully"
    }

    stage('DEPLOY') {
        echo "Deploying Java Application..."
        echo "Deployment Successful!"
    }

}
