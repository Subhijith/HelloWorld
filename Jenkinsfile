pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                // Compile the Java application
                sh 'javac HelloWorld.java'
            }
        }

        stage('Run') {
            steps {
                // Run the Java application
                sh 'java HelloWorld'
            }
        }
    }
}
