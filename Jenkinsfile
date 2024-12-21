pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // Pull code from source control (e.g., Git)
                git 'https://github.com/Subhijith/HelloWorld.git'
            }
        }
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
