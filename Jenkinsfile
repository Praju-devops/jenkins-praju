pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo "praju is Compiling the java source code"
                sh 'echo jenkins Pipeline with Jenkinsfile'
                sh "java --version"
                sh "hello-world.py"
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