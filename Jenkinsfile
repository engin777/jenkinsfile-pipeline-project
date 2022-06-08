pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo 'Compiling the jav source code'
                sh 'javac Hello.java'
            }
        }
        stage('run') {
            steps {
                echo 'Running the compile java code.'
                sh 'java Hello'
            }
        }
    }
}