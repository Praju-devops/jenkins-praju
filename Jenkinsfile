pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo "praju is Compiling the java source code"
                sh "java --version"
                sh 'python hello-world.py'
            }
        }

        stage('run') {
            steps {
                echo "Running the compiled java code"
                sh "java Hello"
            }
        }
    }
}